# Tools Reference

The tools that support each part of the audit, organized by what they do, not by vendor. You can run the entire checklist with the free tools alone. Paid tools speed up the work and add depth, but none are required to start.

A note on philosophy: this is a practitioner reference, not a vendor pitch. Tools change, pricing changes, and the right choice depends on your scale. Pick by capability and budget. Free options are listed first in each category.

---

## Core free stack (start here)

If you use nothing else, use these. They cover the majority of the checklist at zero cost.

| Tool | What it does | Used in tabs |
|---|---|---|
| **Google Search Console** | The source of truth for how Google sees your site: indexing status, queries, clicks, impressions, position, Core Web Vitals, and manual actions | Technical SEO, Weekly Workflow, Monthly Workflow, AIO |
| **Google Analytics (GA4)** | Traffic, engagement, and conversion data to see what your SEO actually drives | Content Audit, Monthly Workflow |
| **Google PageSpeed Insights** | Core Web Vitals and performance scoring with specific fixes | Technical SEO, New Page Launch, SXO |
| **Google Rich Results Test** | Validates your structured data (schema) and shows which rich results a page is eligible for | On-Page SEO, AIO |
| **Google Business Profile** | The control panel for local search presence | Local SEO |
| **Bing Webmaster Tools** | Bing's equivalent of Search Console; also matters because some AI engines draw on Bing's index | Technical SEO |

---

## Crawling and technical audit

For checking crawlability, indexation, broken links, redirects, and site structure.

- **Screaming Frog SEO Spider** (free up to 500 URLs, paid beyond) — the standard desktop crawler. Finds broken links, redirect chains, missing tags, duplicate content, and crawl issues.
- **Sitebulb** (paid) — crawler with stronger visualization and prioritized recommendations.
- **Google Search Console URL Inspection** (free) — checks how Google renders and indexes a specific URL.
- **Browser DevTools** (free, built into Chrome/Firefox) — inspect rendering, network requests, and whether content loads in the initial HTML or via JavaScript. Important for GEO, since AI crawlers may not render JavaScript.

**Tabs:** Technical SEO, New Website Launch, New Page Launch.

---

## Keyword and content research

For finding what to target and assessing topic coverage.

- **Google Keyword Planner** (free with a Google Ads account) — search volume and keyword ideas.
- **Google Trends** (free) — relative interest over time and rising queries.
- **Google autocomplete and "People Also Ask"** (free) — direct insight into the questions searchers ask, which is gold for AEO.
- **Ahrefs** (paid) — comprehensive keyword, difficulty, and content gap data.
- **Semrush** (paid) — keyword research, competitor analysis, and content auditing.
- **AnswerThePublic** (freemium) — question-based keyword discovery, useful for answer engine optimization.

**Tabs:** Content Audit, On-Page SEO, AEO/AIO.

---

## Content quality and E-E-A-T

For assessing depth, uniqueness, and trust signals.

- **Manual review against the checklist** (free) — the Content Audit tab is built to be run by a human reading the page critically. No tool replaces this.
- **Copyscape or similar** (freemium) — checks for duplicate or plagiarized content.
- **Surfer SEO or Clearscope** (paid) — content scoring against top-ranking pages for semantic depth and coverage.
- **Originality.ai** (paid) — AI-content and plagiarism detection, relevant for E-E-A-T where original expertise matters.

**Tabs:** Content Audit.

---

## AI search and GEO tools

For checking how AI engines see and cite your content. This category is new and evolving fast.

- **The AI engines themselves** (free) — the simplest test. Ask ChatGPT, Perplexity, Gemini, and Google AI Overviews questions your content should answer, and see whether you are cited. Do this regularly.
- **robots.txt and llms.txt review** (free, manual) — confirm AI crawlers (GPTBot, ClaudeBot, PerplexityBot, Google-Extended) are not blocked, and consider an `llms.txt` file to guide them.
- **AI visibility trackers** (paid, emerging category) — tools that monitor whether and how often your brand is cited across AI engines. The category is young; evaluate current options against your needs.
- **Schema markup validators** (free: Google Rich Results Test, Schema.org validator) — structured data helps AI engines classify your content.

**Tabs:** GEO — AI Engines, AEO, AIO — AI Overviews.

---

## Backlinks and authority

For link building, anchor analysis, and toxic link detection.

- **Google Search Console Links report** (free) — shows who links to you, your top linked pages, and anchor text, straight from Google.
- **Ahrefs** (paid) — the deepest backlink index, competitor link gap analysis, and toxic link identification.
- **Semrush Backlink Audit** (paid) — backlink analysis with a toxicity score and disavow workflow.
- **Moz Link Explorer** (freemium) — domain authority and link metrics.

**Tabs:** Backlinks & Authority, Monthly Workflow.

---

## Rank tracking and monitoring

For watching positions over time, in both classic and AI search.

- **Google Search Console** (free) — average position by query and page; the most trustworthy ranking data because it is your real data.
- **Ahrefs / Semrush rank tracking** (paid) — daily position tracking across many keywords with SERP feature flags.
- **AI Overview and SERP feature tracking** (paid, varies) — some rank trackers now flag whether a query triggers an AI Overview and whether you appear.

**Tabs:** Weekly Workflow, Monthly Workflow.

---

## Video SEO

- **YouTube Studio** (free) — analytics, and the place to set titles, descriptions, chapters, and thumbnails.
- **Google Video schema** validated via Rich Results Test (free) — helps video appear in search and AI answers.

**Tabs:** YouTube & Video SEO.

---

## Local SEO

- **Google Business Profile** (free) — the core of local presence.
- **NAP consistency checks** (manual or via local SEO tools) — confirm your name, address, and phone match across the web.
- **Local citation and review tools** (varies) — BrightLocal and similar for citation building and review monitoring.

**Tabs:** Local SEO.

---

## How to choose

- **Just starting, no budget:** the core free stack plus Screaming Frog (free tier) and manual AI-engine testing covers most of the checklist.
- **Solo practitioner or small team:** add one paid all-in-one (Ahrefs or Semrush) for keyword, backlink, and rank data in one place.
- **Agency or larger team:** layer in content scoring (Surfer/Clearscope), a dedicated crawler (Sitebulb), and an emerging AI-visibility tracker as that category matures.

Match the tool to the tab and the budget. The checklist is the system; the tools just make running it faster.
