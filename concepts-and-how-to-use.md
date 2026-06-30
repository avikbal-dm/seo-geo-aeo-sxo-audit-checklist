# Concepts & How to Use This Workbook

This guide defines every term the workbook uses and explains how to apply each tab in practice. Read [How Search Works Now](how-search-works-now.md) first for the underlying mechanics; this guide is the practical companion.

---

## The five optimization disciplines

The workbook organizes around five disciplines. They overlap, but each answers a different question.

### SEO — Search Engine Optimization

**The question it answers:** Can search engines find, understand, and rank my page in classic results?

The foundation. SEO covers the technical health of your site (can bots crawl and index it), on-page optimization (is the page clearly about its topic), content quality, and authority (do other sites vouch for you). Everything else builds on this. A page that fails SEO basics rarely succeeds at the AI-era disciplines either, because AI engines retrieve from the same well-built pages classic search rewards.

**Workbook tabs:** Technical SEO, On-Page SEO, Content Audit, Backlinks & Authority.

### GEO — Generative Engine Optimization

**The question it answers:** Can AI engines read my content and pull it into a generated answer?

GEO is about being *retrievable* by AI engines like ChatGPT, Perplexity, Gemini, and Google's AI systems. It focuses on clean rendering (content not trapped in unrendered JavaScript), clear structure that lets an engine isolate relevant passages, crawler access for AI bots, and self-contained passages that make sense when lifted out of the page.

**Workbook tab:** GEO — AI Engines.

### AEO — Answer Engine Optimization

**The question it answers:** Once retrieved, is my content structured to win the direct answer?

AEO is about being *citable*, not just readable. It structures content so an AI (or a featured snippet) can lift a clean, direct answer from it: leading with the answer, using lists and tables, making claims specific and verifiable, and matching the exact question a searcher asks. Where GEO gets you into the candidate pool, AEO gets you chosen.

**Workbook tabs:** AEO concepts run through the GEO and AIO tabs; the AIO tab is the most specific application.

### AIO — AI Overviews Optimization

**The question it answers:** Is my page eligible to be cited in Google's AI Overviews?

AIO is AEO applied specifically to Google's AI Overviews, the AI-generated answers that appear above classic results. It requires the page to rank well already, to contain a direct and concise answer passage, to use a clear extractable structure, and to carry schema markup that helps Google classify the content. Because AI Overviews pull heavily from page-one results, AIO and classic SEO reinforce each other.

**Workbook tab:** AIO — AI Overviews.

### SXO — Search Experience Optimization

**The question it answers:** Does the page actually satisfy the searcher's intent and give them a good experience?

SXO sits across everything. It is about matching what the searcher actually wanted (intent match), delivering it fast and cleanly (UX and Core Web Vitals), and aligning the page with what the rest of the SERP signals the query wants. A page can be technically optimized and still lose if it answers a different question than the one being asked. SXO closes that gap.

**Workbook tab:** SXO — Search Experience.

---

## How the disciplines stack

Think of it as layers, bottom to top:

```
        SXO  (experience and intent, across everything)
   ┌──────────────────────────────────────────────┐
   │   AIO   (eligible for Google AI Overviews)    │
   │   AEO   (structured to win the answer)        │
   │   GEO   (readable and retrievable by AI)      │
   ├──────────────────────────────────────────────┤
   │   SEO   (crawlable, indexable, ranked,        │
   │          quality, authoritative)              │
   └──────────────────────────────────────────────┘
              FOUNDATION FIRST
```

Build from the bottom. The SEO foundation feeds the AI-era layers, because AI engines retrieve from the same indexed, well-structured, authoritative pages that classic search rewards. SXO wraps the whole stack: intent and experience help you at every layer.

---

## How to use each tab

### 1. Start Here
The dashboard. Read it first to understand the workbook layout and the recommended order. Return to it when onboarding a teammate.

### 2. New Website Launch
Run this once per new site, before and after launch. It is a site-wide gate covering technical setup, crawl readiness, brand and trust signals, and the foundations a new domain needs. Do not publish a new site without clearing it.

### 3. New Page Launch
Run this every time you publish a new page. It is the pre-publish quality gate: SEO basics, content structure, intent match, schema, and Core Web Vitals. Two minutes of checking here prevents a page that quietly underperforms for months.

### 4. Content Audit
Run monthly or quarterly across your existing content. It hunts for redundancy, thin or duplicate pages, weak E-E-A-T, and shallow topic coverage. This is where you find pages to improve, merge, or remove.

### 5. Technical SEO
Run monthly. The full technical sweep: crawlability, indexation, site speed, mobile, security, and structured data. This is the foundation health check. Schedule it so it does not slip.

### 6. On-Page SEO
Run every time you create or edit a page. Title, meta description, headings, copy quality, internal links, image optimization, and per-page schema. The per-page companion to the technical tab.

### 7. GEO — AI Engines
Run on every page where AI visibility matters. Checks that AI engines can crawl, render, and retrieve your content: AI bot access, clean rendering, clear structure, and self-contained passages.

### 8. SXO — Search Experience
Run on every important page. Checks intent match (does the page answer the actual query), UX signals, and alignment with what the SERP rewards for that query. Catches the "optimized but wrong" problem.

### 9. AIO — AI Overviews
Run on pages targeting queries that trigger AI Overviews. Checks the specific signals for AI Overview citation eligibility: a direct answer passage, extractable structure, schema, and existing ranking strength.

### 10. Backlinks & Authority
Run monthly. Link building progress, anchor text health, toxic link identification, and competitor backlink gaps. The authority half of SEO.

### 11. YouTube & Video SEO
Run for every video you publish. Titles, descriptions, chapters, video schema, and embedding. Video is its own retrieval surface and an increasingly common AI Overview source.

### 12. Local SEO
Run for local-intent sites. Google Business Profile completeness, NAP (name, address, phone) consistency, local schema, citations, and review health.

### 13. Weekly Workflow
Run every week. The recurring maintenance loop: Search Console checks, rank monitoring, and quick fixes. Keeps small problems from becoming big ones.

### 14. Monthly Workflow
Run every month. The deeper recurring review: content refresh candidates, link audit, and competitor gap analysis. The strategic counterpart to the weekly loop.

### 15. Priority Tracker
Keep this open always. It is the status board across every sheet, showing what is done, in progress, and pending, so nothing falls through the cracks.

---

## A suggested operating rhythm

| Cadence | Tabs to run |
|---|---|
| Every new page | New Page Launch, On-Page SEO, GEO, SXO, AIO (if relevant) |
| Every new site | New Website Launch (then the per-page tabs as you build) |
| Every week | Weekly Workflow |
| Every month | Monthly Workflow, Technical SEO, Backlinks & Authority |
| Every quarter | Content Audit (full sweep) |
| Always open | Priority Tracker |

Start where your biggest gap is. If you have never run a technical audit, start with Technical SEO. If your pages rank but AI engines never cite you, start with GEO and AIO. The workbook is modular: you do not have to run every tab to get value from one.

For the reasoning behind each check, see [How Search Works Now](how-search-works-now.md). For the tools that support each audit, see the [tools reference](tools-reference.md).
