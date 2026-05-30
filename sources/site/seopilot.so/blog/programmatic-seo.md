# Source: https://seopilot.so/blog/programmatic-seo

[← Back to blog](https://seopilot.so/blog)

![lines of HTML codes](https://images.unsplash.com/photo-1542831371-29b0f74f9713?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5NTYyMzJ8MHwxfHNlYXJjaHwxfHxwcm9ncmFtbWF0aWMtc2VvfGVufDF8MHx8fDE3Nzk0MTYwMzV8MA&ixlib=rb-4.1.0&q=80&w=1080)

Photo by [Florian Olivo](https://unsplash.com/@florianolv?utm_source=seopilot&utm_medium=referral) on [Unsplash](https://unsplash.com/photos/lines-of-html-codes-4hbJ-eymZ1o?utm_source=seopilot&utm_medium=referral)

If you've Googled "\[any city\] coffee shops" or "\[App A\] vs \[App B\] integration," you've already used programmatic SEO. Wise has built 8.5 million currency converter pages. Zapier has 6,000+ integration pages. Tripadvisor and Yelp have built their entire businesses on it.

For a small SaaS founder who can write code, programmatic SEO is the highest-leverage SEO move available. One Friday night you build a template. By Monday you're targeting 2,000 long-tail queries that would have taken a year to write by hand.

It also has the highest blast radius for getting it wrong. Most programmatic SEO attempts fail not because Google hates pSEO — Google indexes Wise and Zapier just fine — but because the founder shipped templates with no actual content underneath them.

This is how to do it without becoming the kind of site Google's helpful-content system was built to suppress.

## What programmatic SEO actually is

Programmatic SEO (pSEO) is a content strategy where you:

1. Identify a _pattern_ of search query — usually `[modifier] + [variable]`, like "best \[city\] \[profession\]" or "convert \[from currency\] to \[to currency\]"
2. Build a _page template_ that answers that query
3. Combine the template with a _dataset_ — every variation of the variables
4. Publish at scale, often hundreds or thousands of pages

Each page lives at its own URL, has its own metadata, and ranks independently. Google treats them as normal pages. The only thing "programmatic" about them is how they were generated.

## The four ingredients

Every working programmatic SEO project has the same four ingredients. Skip any of them and the project fails.

### 1\. A query pattern with real demand

Open Keywords Everywhere or Google Trends. Search for a few variations of your candidate pattern and check the volume.

Good signs: total combined volume across variants is >5,000/mo, the pattern is genuinely how people search (not just how SEOs search), and the existing top results are mediocre.

Bad signs: each variant has volume but the pattern is too commercial (e.g. "\[product\] discount code"), or the pattern is already dominated by listings sites that rank by user-generated content (Yelp, Tripadvisor, Reddit).

### 2\. A dataset

The dataset is what makes the pages non-thin. It's also the part most founders skip.

Examples of good datasets:

- **Proprietary data** — your own usage stats, surveys, or research
- **Public APIs** — currency rates, weather, sports stats, government data
- **Aggregated public information** — restaurant menus, business hours, university rankings
- **Computed data** — calculator results, conversions, lookup tables

The data has to be _useful on the page_. A "best CRM in \[city\]" page that just lists the same five CRMs everywhere is thin. A "best CRM in \[city\]" page that also surfaces local pricing, regulatory considerations, and language support per city is not.

### 3\. A template that doesn't read like a template

The biggest tell of bad programmatic SEO is the obvious mad-libs structure: "Looking for a CRM in \[city\]? You'll love our list of CRMs in \[city\]. Here are the top 5 CRMs in \[city\]…"

Google's models can detect this in milliseconds. So can users.

A working template uses the variable as _a parameter_, not as filler. The page sections are oriented around the data, not around the keyword. The keyword appears naturally in headings and metadata but doesn't dominate the prose.

### 4\. Internal linking and discoverability

A thousand orphan pages are worth nothing. Each programmatic page needs:

- A predictable URL pattern
- Inclusion in the sitemap
- Internal links from at least one other page (usually a hub or category page)
- Optionally, links to and from related programmatic pages

Without this, Google won't crawl most of your pages and the ones it does crawl will look like islands.

## Real examples that work

**Zapier — integration pages.** Pattern: `/apps/[App A]/integrations/[App B]`. Volume comes from queries like "Notion + Slack integration." The dataset is Zapier's own integration graph plus user examples. Each page describes the actual workflows users build. Result: thousands of ranking pages, most of them position 1–3 for their long-tail queries.

**Wise — currency converter pages.** Pattern: `/[from-currency]-to-[to-currency]`. Dataset: real-time mid-market rates plus historical charts plus bank comparison. Each page answers a specific transactional query and links into Wise's product. Result: dominant SEO presence for almost every currency-conversion query that exists.

**Tripadvisor — destination pages.** Pattern: `/Attractions-[city]-[country]`. Dataset: user reviews, photos, ratings — the moat. Templated SEO works here because the dataset is unique and grows weekly.

**Numbeo — cost-of-living pages.** Pattern: `/cost-of-living/in/[city]`. Dataset: crowdsourced price submissions. Pages have real numerical data nobody else has.

The common thread: each example has a _dataset that competitors cannot trivially replicate_. Programmatic SEO without a moat is a race to the bottom.

## When programmatic SEO is the wrong move

It's not the right play for everyone. Skip pSEO if any of the following are true:

- You don't have a dataset that's at least somewhat unique. Generic content at scale is exactly what Google's been suppressing for two years.
- Your audience is small (B2B with a niche audience under ~5k decision-makers). pSEO trades against the thing that matters more for you: a few really deep, opinionated articles.
- Your product doesn't naturally tile across a variable. Forcing a programmatic angle onto a product that's about a single category usually produces awkward content nobody searches for.
- You can't write code or commit a few weeks of engineering. pSEO done by hand or in a spreadsheet is just slow regular SEO.

## How to ship a programmatic SEO project

### Programmatic SEO in five steps

1. 1
 
 Find the pattern
 
 Use Keywords Everywhere or Ahrefs to find a long-tail query pattern with combined volume above 5,000/mo. Validate with Google searches that the SERP isn't already dominated by entrenched user-generated content sites.
 
2. 2
 
 Source the data
 
 Identify a dataset — proprietary, public, or computed — that gives each page genuine non-templated value. If you can't find one, the project doesn't work.
 
3. 3
 
 Build the template
 
 One page in production code. Real headings, real prose, real linkages to your product where natural. Get a human reviewer to look at five rendered variants and judge if they read like distinct pages.
 
4. 4
 
 Generate, sitemap, link
 
 Build the full set. Add to sitemap. Wire each page into a hub or category page so Google can crawl it. Add internal links between related pages.
 
5. 5
 
 Monitor and iterate
 
 Watch GSC. Most pages will start showing impressions in 2–6 weeks. Some will rank, others won't. Iterate the template based on which sub-patterns are working.
 

The whole loop usually takes 4–8 weeks for a first project. The second project takes a weekend.

## The Google quality bar

Google's spam policies and Helpful Content guidelines explicitly call out "scaled content abuse" — generating large numbers of pages with little or no original value. The threshold isn't "you used a template" (Wise and Zapier use templates). The threshold is "is each page actually helpful to the person who searched the query?"

Two practical tests before launching:

1. Read three randomly chosen rendered pages end-to-end. Would you keep reading if you'd landed on them organically? If no, the template needs more substance.
2. Compare your page to the current top-ranking page for the same query. Is yours better, worse, or just different? "Different" is fine. "Worse" is a flag.

If the project fails these tests, don't ship it. You'll spend more time fighting an algorithmic deindexing later than you'll save by launching now.

## Comparison: working pSEO vs. spam pSEO

| Dimension | Working pSEO | Spam pSEO |
| --- | --- | --- |
| Dataset | Proprietary, public-but-aggregated, or computed | None — same content reordered |
| Template | Variables drive structure; prose reads naturally | Mad-libs filler — keyword stuffed in every paragraph |
| Per-page value | Genuinely useful information unique to the variant | Same advice, different headline |
| Volume of pages | Hundreds to thousands — matched to dataset size | Tens of thousands of empty variants |
| User behavior | Pages get clicks, time on page, return visits | High bounce, no engagement |

## Frequently Asked Questions

### Is programmatic SEO against Google's guidelines?

No, programmatic SEO itself isn't against the guidelines. Google's Search Central documentation explicitly says automated content is fine _if it provides original value to users_. What's against the guidelines is "scaled content abuse" — publishing large volumes of low-value pages whose primary purpose is ranking, not helping users. The line is the per-page value of your content, not the method by which it was produced.

### What's the minimum dataset size for programmatic SEO to be worth it?

Roughly 100 pages is the lower bound where the engineering effort pays off, and 1,000+ is where compounding starts. Below 100, you might as well write the pages by hand. Above 10,000, you need to be especially careful about quality, indexing, and crawl budget — Google won't index every page on a new domain just because you published it.

### How long until programmatic SEO pages start ranking?

Most programmatic pages start showing impressions within 2–6 weeks of being indexed and start ranking on page 1 for the easier long-tail variants in 3–6 months. Highly competitive variants may never rank without supporting content and backlinks. Plan for a 6–12 month horizon before judging whether the project worked.

### Do I need a CMS to do programmatic SEO?

No. Most programmatic SEO sites use a static site generator (Next.js, Astro, Hugo, 11ty) that reads a JSON, CSV, or database file at build time and emits one HTML page per row. This is faster, cheaper, and easier to maintain than a CMS for thousands of templated pages. Use a CMS only if non-engineers need to edit the dataset directly.

### Can I do programmatic SEO with AI-generated content?

Yes, but carefully. AI is excellent for generating per-page sections that are genuinely informed by the page's variables (like a localized intro paragraph for each city page). It's a trap when used to generate the _whole page_ with no underlying data — that's the spam pSEO pattern Google's quality systems are tuned to detect. Use AI to enrich a real dataset, not to substitute for one.

## The one-line summary

Programmatic SEO is templated pages backed by real data. If you have the data, it's the highest-leverage SEO move you can make. If you don't, no template will save you.

Find the dataset first. The template is the easy part.

See SEOPilot in action

## Turn SEO advice into a publishing system

Run your site through SEOPilot to find realistic keyword opportunities and publish in a steady rhythm.

[See how much traffic your site is missing](https://seopilot.so/) [Browse more articles](https://seopilot.so/blog)

[← Back to all posts](https://seopilot.so/blog)