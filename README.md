# smart-admin-
# Smart Admin Assist — AI Workplace Productivity

A focused AI productivity dashboard built with **TanStack Start**, **React**, and **Tailwind CSS**. Smart Admin Assist bundles five workplace tools — email drafting, meeting notes summarisation, task planning, research briefing, and a general assistant chat — behind a single, calm, editorial-style UI.

## Live Demo

- Preview: `https://<your-preview-url>.lovable.app`
- Published: `https://<your-published-url>.lovable.app`

## Features

- **Smart Email Generator** — Draft tone-matched professional emails from a topic, recipient, tone, length, and short context brief.
- **Meeting Notes Summarizer** — Turn raw notes or a transcript into a summary with decisions, owners, action items, and deadlines — without inventing names or dates.
- **AI Task Planner** — Convert a messy task list into a prioritised (P1–P3), time-blocked schedule that respects working hours, energy patterns, and fixed commitments.
- **AI Research Assistant** — Summarise a topic or pasted article into key points, insights, next steps, and what to fact-check (no live web access, and the UI says so).
- **Assistant Chat** — Freeform chat for drafting help, prioritisation, and quick workplace questions, with suggested starter prompts.
- **Consistent Generate Workspace** — Shared `GenerateWorkspace` component gives every tool the same input → prompt → output pattern, with chips summarising the current settings.
- **Resilient by design** — Server-function calls are wrapped in try/catch with toast notifications on failure, so a flaky AI response never breaks the page.
- **Responsive shell** — Shared `AppShell` layout with eyebrow/title headers keeps navigation and framing consistent across tools.

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | TanStack Start |
| UI Library | React |
| Styling | Tailwind CSS |
| Routing | TanStack Router (file-based) |
| Data/Server | TanStack Query + TanStack Start server functions |
| Notifications | Sonner |
| Icons / UI primitives | shadcn/ui-style components |

## Project Structure
