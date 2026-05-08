# Philip MacDonald — Marketing Manager

Most marketing managers use tools. I also build them.

My day job is running full-funnel marketing — campaigns, SEO, CRM, analytics. On top of that I build the automation layer that makes the rest faster: Claude-integrated workflows, Cloudflare Workers, n8n pipelines, Python scrapers. Everything here came out of a real problem I needed to solve.

---

## Projects

### [ai-marketing-briefing](https://github.com/philip95macdonald-cmd/ai-marketing-briefing)
Every morning at 07:30, Claude reads my Google Calendar and Notion task board and sends a prioritised briefing to Slack — before the first meeting. Built because context-switching between three tools to plan the day is a waste of 20 minutes.

`Claude API` `Google Calendar` `Notion` `Slack` `GitHub Actions`

---

### [content-seo-engine](https://github.com/philip95macdonald-cmd/content-seo-engine)
Replaced Clearscope with three scripts: Claude generates data-driven briefs, a deterministic scorer grades finished posts on 5 SEO/E-E-A-T/GEO dimensions (100 pts), and a schema generator outputs production-ready JSON-LD. Used in a real editorial workflow.

`Claude API` `SEO` `JSON-LD` `E-E-A-T` `GEO`

---

### [seo-audit-toolkit](https://github.com/philip95macdonald-cmd/seo-audit-toolkit)
Two scripts: on-page technical auditor (10 signals, runs in 2 seconds on any URL) and a Google Search Console report that pulls top queries, clicks, CTR, and position for the last 28 days — without opening a browser.

`Google Search Console API` `Technical SEO` `Node.js`

---

### [lead-pipeline](https://github.com/philip95macdonald-cmd/lead-pipeline)
Form-to-ESP handler on Cloudflare Workers. CORS, rate-limiting, honeypot bot detection, GDPR consent timestamps, and an adapter pattern that lets you swap Brevo for HubSpot or Mailchimp by changing one env var.

`Cloudflare Workers` `Brevo` `GDPR` `Marketing Automation`

---

### [webhook-n8n-bridge](https://github.com/philip95macdonald-cmd/webhook-n8n-bridge)
Cloudflare Worker between any signed webhook source and n8n. Verifies HMAC-SHA256 or Stripe-style signatures, deduplicates retries, then forwards to n8n — so the automation logic lives in n8n, not scattered across glue code.

`Cloudflare Workers` `n8n` `Webhooks` `HMAC`

---

### [ngo-stakeholder-stack](https://github.com/philip95macdonald-cmd/ngo-stakeholder-stack)
Python toolkit for NGO stakeholder communication: press contact crawler (robots.txt-compliant, NER-based, 49 tests), politician data from Abgeordnetenwatch, topic + crisis monitor, Brevo sync. Generalized from a production stack that replaced ~80% of a Meltwater subscription.

`Python` `Playwright` `NLP` `Brevo` `DSGVO-compliant`

---

## Stack

| Area | Tools |
|---|---|
| AI / LLM | Claude (Anthropic), custom prompt pipelines |
| Automation | n8n, Cloudflare Workers, GitHub Actions |
| CRM & Email | Brevo, HubSpot, Salesforce |
| Analytics | GA4, Google Search Console, Google Ads, GTM |
| Content | Higgsfield (AI video), custom SEO scoring |
| Infrastructure | Cloudflare, Notion, Slack |

---

*Germany · Open to roles where marketing and engineering overlap*
