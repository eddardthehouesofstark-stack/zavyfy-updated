# ApprovalIQ — AICTE Approval Intelligence

Responsive React/Vite prototype for an AI-assisted institutional approval workflow.

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```

Production build: `npm run build` and `npm run preview`.

## Included
- Executive dashboard with KPI cards, application trends, risk distribution, compliance, and document verification.
- Application register with search, filters, sorting, multi-select, and CSV export.
- Application detail tabs: Overview, Documents, Infrastructure, Faculty, Compliance, AI Findings, Institution Memory, Timeline, Audit Logs.
- AI processing screen with eight agents and animated progress.
- Evidence-linked AI findings with severity, confidence, rule references, and recommendations.
- Compliance center, institution memory, smart inspection, analytics, reports, officer workspace, intake forms, and settings.
- Ctrl/Cmd+K command palette, notification popover, profile menu, dark/light mode, responsive navigation, toast feedback.

## Stack
React 18, Vite, Recharts, lucide-react, custom CSS design system, Inter font.

## Important demo notice
All institution records, metrics, AI findings, and example rule references are illustrative demo data. This is not connected to AICTE systems; it does not submit official applications, schedule real inspections, or make real approval decisions. Before production use, connect a secure backend, validate official rules for the applicable academic year, implement authentication/authorization and document security, audit model quality, and retain human-authorised decisions.
