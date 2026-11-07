# Awesome Aurelix

A list of the Aurelix web data tools on the Apify Store, each with a runnable example repo.

Each public tool also has a page with its live price, example input and output, and FAQ on the [Aurelix tools site](https://aurelix-solutions.github.io/tools/).

All tools read only public pages with no login and are paid per result on Apify (see each tool's Store page for current prices). Each entry says why it beats the leading alternatives on the Apify Store, from the comparison table on its Store page. Example repos hold MIT-licensed Python that calls the tool with `apify-client` and writes a CSV.

## Contents

- [Jobs and hiring](#jobs-and-hiring)
- [E-commerce and product research](#e-commerce-and-product-research)
- [Leads and local business](#leads-and-local-business)
- [Ad research](#ad-research)
- [Public records](#public-records)
- [Web and AI](#web-and-ai)
- [Marketing and SEO research](#marketing-and-seo-research)
- [Recipes](#recipes)

## Jobs and hiring

- [LinkedIn Jobs Scraper](https://apify.com/aurelix/linkedin-jobs) - LinkedIn job postings by keyword, country and date posted, with no login: title, company, location, salary where shown, seniority and description. Why this one: exact country filter and filtered-out jobs free; 25% under the most-used LinkedIn scraper. Example: [linkedin-jobs-example](https://github.com/Aurelix-Solutions/linkedin-jobs-example).
- [Greenhouse Jobs Scraper](https://apify.com/aurelix/greenhouse-jobs-scraper) - Jobs straight from company career sites on Greenhouse, Lever, Ashby and SmartRecruiters, in one schema with salary, remote flag and apply link. Why this one: 8x cheaper than the leading jobs API and 40% under the leading feed, read live from each employer's board. Example: [career-site-jobs-example](https://github.com/Aurelix-Solutions/career-site-jobs-example).
- [Multi Job Board Scraper](https://apify.com/aurelix/multi-job-board-scraper) - One job search across LinkedIn, company career sites and remote boards, with duplicates merged into one schema. Why this one: LinkedIn plus ~50 company career sites in one deduplicated search, 25% under the alternatives. Example: [multi-board-jobs-example](https://github.com/Aurelix-Solutions/multi-board-jobs-example).

## E-commerce and product research

- [Amazon Best Sellers Scraper](https://apify.com/aurelix/amazon-best-sellers) - Amazon Best Sellers and New Releases by category in 10 marketplaces (US, UK, DE, FR, IT, ES, CA, AU, IN, JP): rank, ASIN, price, rating and reviews, plus rank changes since your last run. Why this one: 69% under the most-used Best Sellers scraper ($1.80 vs $5.90 per 1,000), 10 marketplaces incl. amazon.ca. Example: [amazon-best-sellers-example](https://github.com/Aurelix-Solutions/amazon-best-sellers-example).
- [Amazon Product Search Scraper](https://apify.com/aurelix/amazon-product-search) - Amazon search results for any keyword on amazon.com and amazon.ca, in page order: position, organic position, sponsored flag, ASIN, price, list price, rating, reviews and badges. Why this one: $0.20 per 1,000 products vs $1.00-$5.00 for the leading Amazon search scrapers, one row per product even when it is both an ad and an organic result, and an only-new-products mode. Example: [amazon-product-search-example](https://github.com/Aurelix-Solutions/amazon-product-search-example).
- [AliExpress Scraper](https://apify.com/aurelix/aliexpress-product-search) - AliExpress search results for any keyword: price, original price, discount, rating, units sold and ship-from country. Why this one: cheapest of the three we compared ($1.80 vs $2.49-$9.00 per 1,000), sponsored results flagged. Example: [aliexpress-product-search-example](https://github.com/Aurelix-Solutions/aliexpress-product-search-example).

## Leads and local business

- [Google Maps Business Scraper](https://apify.com/aurelix/google-maps-scraper) - Google Maps business listings by keyword and city: categories, address, phone, website, rating, hours and coordinates. No review text. Why this one: $1.50 per 1,000 places, less than half the leading Google Maps scrapers ($4-5), with many cities per run and an only-new-places mode. Example: [google-maps-businesses-example](https://github.com/Aurelix-Solutions/google-maps-businesses-example).
- [Recently Funded Companies](https://apify.com/aurelix/recently-funded-companies) - US companies that just raised a private round, from official SEC Form D filings: offering size, amount sold, industry, executives and directors, plus an optional website and contacts. Why this one: funds and SPVs removed by default, a free only-new-filings mode and the company website confirmed against the filing, which the Form D alternatives compared do not offer. Example: [recently-funded-companies-example](https://github.com/Aurelix-Solutions/recently-funded-companies-example).
- [Funded Companies Hiring](https://apify.com/aurelix/funded-companies-hiring) - US companies that just raised money (new SEC Form D) joined to their confirmed website, every open role on their own job board and the business contacts they publish, as a monitor that alerts only on new raises and new roles. Why this one: $20 per 1,000 hiring companies against $30 for the other Form D plus jobs Actor, seven job-board systems including Workday instead of three, and company contacts charged only when found. Example: [funded-companies-hiring-example](https://github.com/Aurelix-Solutions/funded-companies-hiring-example).

## Ad research

- [Facebook Ad Library Scraper](https://apify.com/aurelix/facebook-ad-library-scraper) - Business ads from the public Meta Ad Library by keyword, page ID or Ad Library URL: ad text, media links, dates and platforms. Political ads excluded. Why this one: $0.70 per 1,000 ads vs $5.80 for Apify's own Facebook Ads Scraper, with exact limits and a new-ads-only mode. Example: [facebook-ad-library-example](https://github.com/Aurelix-Solutions/facebook-ad-library-example).
- [Competitor Watch](https://apify.com/aurelix/competitor-watch) - One report per competitor with only what is new since the last run: new Meta and TikTok ads, text changes on chosen pages, new and re-priced Shopify products and new job postings, plus a Slack or webhook digest. Why this one: five sources in one run and one plain-language summary per competitor, $0.03 per competitor per run plus $0.001 per new item, instead of five scrapers and five schedules. Example: [competitor-watch-example](https://github.com/Aurelix-Solutions/competitor-watch-example).

## Public records

- [Canada Building Permits Scraper](https://apify.com/aurelix/canada-building-permits-scraper) - Development applications and building permits from seven Canadian cities' open data: address, ward, type, status and value. No owner names. Why this one: the only one with development applications and a ward filter, and the cheapest of the three ($3.00 vs $3.50-$5.00). Example: [canada-development-applications-example](https://github.com/Aurelix-Solutions/canada-development-applications-example).

## Web and AI

- [Website to Markdown Crawler](https://apify.com/aurelix/website-to-markdown) - Each page of a website as clean Markdown of its main content for AI, RAG and LLMs, with title, headings and links. Why this one: a flat $1.50 per 1,000 pages, 34% under Apify's RAG Web Browser and no compute-unit billing; failed pages free. Example: [website-to-markdown-example](https://github.com/Aurelix-Solutions/website-to-markdown-example).
- [SEO Audit Crawler](https://apify.com/aurelix/seo-audit-crawler) - A technical SEO audit of every page and the XML sitemap: status, redirects, meta tags, H1, canonical, noindex and broken links. Why this one: 1/16 the price of the most-used per-page SEO audit Actor, broken links and sitemap gaps included. Example: [seo-audit-crawler-example](https://github.com/Aurelix-Solutions/seo-audit-crawler-example).
- [PDF to Markdown Converter](https://apify.com/aurelix/pdf-to-markdown) - PDF and Word (DOCX) files from URLs as Markdown per page, with tables as JSON rows, AI-ready chunks and automatic OCR for scanned pages. Why this one: $0.003 for a 10-page PDF vs $0.005 and $0.00345 for the alternatives compared, with Word files and OCR at $8 per 1,000 pages. Example: [pdf-to-markdown-example](https://github.com/Aurelix-Solutions/pdf-to-markdown-example).

## Marketing and SEO research

- [Google Trends Scraper](https://apify.com/aurelix/google-trends-scraper) - Google Trends for any number of keywords on one 0-100 scale: interest over time, interest by country, state, metro or city, and top and rising related queries. Why this one: $1.50 per 1,000 results vs $3.00 plus platform usage for Apify's own Google Trends Scraper, and it accepts Google Trends explore links. Example: [google-trends-example](https://github.com/Aurelix-Solutions/google-trends-example).
- [Google Autocomplete Scraper](https://apify.com/aurelix/google-autocomplete-scraper) - Keyword ideas from Google Search and YouTube autocomplete: A-Z, 0-9, question and preposition modifiers for every seed, country and language, with intent tags. Why this one: $0.45 per 1,000 keywords vs $0.50-$1.00, and YouTube suggestions in the same run where the alternatives compared are Google only. Example: [keyword-expander-example](https://github.com/Aurelix-Solutions/keyword-expander-example).

## Recipes

Each recipe passes one tool's output field into another tool's input field. Field names are the real ones from each tool's output and input.

### Audit the websites of a local niche

1. [Google Maps Business Scraper](https://apify.com/aurelix/google-maps-scraper) for a niche and city.
2. Pass each `website` as `siteUrl` to [SEO Audit Crawler](https://apify.com/aurelix/seo-audit-crawler). It audits one site per run, so start one run per website (a loop in the example script or an n8n loop).
3. Each run ends with a summary row listing the site's issues by rank.

## Licence

This list is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The tools it links to are separate paid services on the Apify Store.
