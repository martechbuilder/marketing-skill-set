# Philip MacDonald

Marketing Manager with a habit of building the tools I need instead of waiting for someone else to build them.

My stack spans the full marketing funnel — from lead capture and CRM to content, SEO, and AI-assisted automation. Most of what's here started as an internal solution to a real problem.

---

## Projects

### [ai-marketing-briefing](https://github.com/philip95macdonald-cmd/ai-marketing-briefing)
Daily briefing automation for marketing managers. Pulls Google Calendar events and Notion tasks, generates a prioritised summary via Claude, delivers it to Slack before the first meeting. Runs on a GitHub Actions schedule — zero infrastructure to maintain.

`Node.js` `Claude API` `Google Calendar` `Notion` `Slack` `GitHub Actions`

---

### [content-seo-engine](https://github.com/philip95macdonald-cmd/content-seo-engine)
Three tools for data-driven content: Claude generates a full content brief from topic + keyword + audience; a scorer grades finished posts on 5 SEO/E-E-A-T/GEO dimensions (100 pts); a schema generator outputs Article + BreadcrumbList + FAQPage JSON-LD.

`Node.js` `Claude API` `SEO` `JSON-LD` `E-E-A-T`

---

### [lead-pipeline](https://github.com/philip95macdonald-cmd/lead-pipeline)
Form-to-ESP handler on Cloudflare Workers. Validates input, rate-limits by IP, catches bots via honeypot, enforces GDPR consent with a server-side timestamp. Brevo is wired up by default — swap the adapter for any other ESP without touching the core logic.

`Cloudflare Workers` `Brevo` `GDPR` `CORS` `JavaScript`

---

### [webhook-n8n-bridge](https://github.com/philip95macdonald-cmd/webhook-n8n-bridge)
Cloudflare Worker that sits between any signed webhook source and n8n. Verifies HMAC-SHA256 or Stripe-style signatures, deduplicates retries via KV, then forwards to an n8n Webhook node — so automation logic stays in n8n, not in glue code.

`Cloudflare Workers` `n8n` `Webhooks` `HMAC` `Idempotency`

---

### [seo-audit-toolkit](https://github.com/philip95macdonald-cmd/seo-audit-toolkit)
On-page SEO auditor that fetches any URL and scores 10 technical signals; plus a Google Search Console report that pulls top queries, clicks, impressions, CTR and position for the last 28 days.

`Node.js` `Google Search Console API` `SEO` `Technical Audit`

---

### [ngo-stakeholder-stack](https://github.com/philip95macdonald-cmd/ngo-stakeholder-stack)
Python toolkit for NGO stakeholder communication. Crawls press contacts, syncs politicians from Abgeordnetenwatch, monitors topics and crises, builds impact stories — all feeding into Brevo. Generalized from a production press stack that replaced ~80% of a Meltwater subscription.

`Python` `Brevo` `NLP` `Playwright` `DSGVO-compliant`

---

## What I work with

| Area | Tools |
|---|---|
| Marketing Automation | n8n, Google Tag Manager, Webhook pipelines |
| CRM & Email | Brevo, HubSpot, Salesforce |
| Analytics | GA4, Google Search Console, Google Ads |
| AI & Content | Claude, Higgsfield, custom LLM workflows |
| Infrastructure | Cloudflare, Notion, Slack |

---

*Based in Germany. Open to roles where marketing and engineering overlap.*
