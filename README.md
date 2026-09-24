<!-- Idioma / Language --> **English** · [Español](README.es.md)

# Hi, I'm Agustín 👋

Programming Technician (UTN Bahía Blanca). I automate processes and build internal
systems with AI for industrial companies. What I build ships to production and gets used
every day by office staff, field workers and clients.

📍 Bahía Blanca, Argentina · ✉️ agusalvarezm3@gmail.com

## What I work on

| System | What it solves | Stack |
|---|---|---|
| **Container certificates** (Tecnophos ↔ ARCOR) | Photo in WhatsApp → cascading OCR (Groq → Claude) → ISO 6346 validation → client portal → Google Sheets. No human in the loop for the normal case. | Python, FastAPI, n8n, Evolution API, Docker, PostgreSQL |
| **Gestión** (HR · Sales · Observability) | Employee files, expiring certifications, monthly documentation, stock, mobile CRM and an observability panel. ~110 employees. | Next.js 16, React 19, Supabase (RLS), Cloudflare R2, Vercel |
| **ADC–UNIPAR operations** | Seven auditable modules for an industrial cleaning contract, with client-facing access. | Next.js, Supabase, pdf-lib |
| **Appointment system for clinics** | Multi-tenant, token-based patient identity (no national ID), zero clinical data, WhatsApp Cloud API reminders, deposit payments via Mercado Pago. | Next.js, Supabase, Vitest, n8n |
| **Offline field apps** | Pest control and digital work orders with on-screen signatures and a PDF that replicates the official paper form. | HTML, jsPDF, Google Apps Script |
| **Agronomic prescriptions (RPA)** | Monthly filing of prescriptions for eight plants in the Buenos Aires Province Ministry of Agriculture system. | Python, Playwright |

Most of these repos are private because they hold client and employee data.
If you'd like to see code, reach out and we can set up a demo.

## Tools

`TypeScript` `Next.js` `React` `Tailwind` `Supabase` `PostgreSQL` `Python` `FastAPI` `Playwright`
`n8n` `Docker` `Caddy` `Vercel` `Cloudflare R2` `Claude API` `Groq` `WhatsApp Cloud API` `Claude Code`

## How I work

- Short-lived branches, pull requests and code review before anything reaches `main`.
- Security starts at the data model: permission-based Row Level Security, ownership checks, secrets kept out of the repo.
- Documentation for whoever comes next: every project has its `README`, its business context and its decision log.
- I use AI agents (Claude Code) as part of the workflow, with the same review bar as any other change.

## Education

- **Programming Technician degree (Tecnicatura Universitaria en Programación)** — UTN Bahía Blanca, 2023–2025
