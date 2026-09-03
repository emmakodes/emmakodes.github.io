# emmakodes.github.io

Emmanuel Onwuegbusi's personal portfolio site: a hand-authored static site (no build tooling) served directly from the repo root via GitHub Pages.

## Language

**AI Automation Workflow**:
A published case-study entry showcasing a built automation (e.g. an n8n workflow) that solves a real operational problem for its target audience. The unit of content on the `/vc-agents/` listing page.
_Avoid_: Project (too generic, collides with the homepage's unrelated "Featured Projects"/"Previous Projects" sections), Case study (used only when referring to the deeper explanation within an entry, not the entry itself).

**AI Agent**:
The specific AI decision-making component *inside* an AI Automation Workflow (e.g. the LLM node that decides FIT/MAYBE/REJECT) — not the whole workflow. Mirrors the real node naming inside the underlying n8n builds (a workflow contains plumbing nodes plus one or more literal "AI Agent" nodes).
_Avoid_: Using "agent" to refer to an entire workflow.

**Sanitized Export**:
The downloadable workflow JSON published alongside an AI Automation Workflow entry, with personal identifiers (real email addresses, Slack channel IDs, etc.) redacted before publishing. Distinct from the live, real-valued workflow running in the author's own n8n instance, which is never altered — sanitization only ever applies to the copy that gets published.
_Avoid_: "Export" alone (ambiguous about whether it's the real or sanitized version).

**Fictitious VC Disclaimer**:
A small, understated, per-entry note (not a prominent banner) clarifying that a workflow was demonstrated against a fictitious VC firm's invented investment thesis, not a real client engagement. Repeated on every entry rather than stated once, but kept low-key.

**AI Automation Workflows page**:
The `/vc-agents/` section: a paginated series of genuinely separate static HTML pages (not one JS-paginated page), 6 AI Automation Workflow entries per page, built this way specifically so every entry is plain crawlable HTML for search engines. Linked from the homepage nav, and also the page handed out directly in cold outreach.
_Avoid_: Single infinite-scroll or JS-toggled page (rejected — weaker for SEO on a no-build-tooling static site).

