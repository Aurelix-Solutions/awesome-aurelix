# Awesome Aurelix

A list of the Aurelix web data tools on the Apify Store, each with a runnable example repo.

All tools read only public pages with no login and are paid per result on Apify (see each tool's Store page for current prices). Each entry says why it beats the leading alternatives on the Apify Store, from the comparison table on its Store page. Example repos hold MIT-licensed Python that calls the tool with `apify-client` and writes a CSV.

## Contents

- [Jobs and hiring](#jobs-and-hiring)
- [E-commerce and product research](#e-commerce-and-product-research)
- [Leads and local business](#leads-and-local-business)
- [Public records](#public-records)
- [Marketing and SEO research](#marketing-and-seo-research)

## Jobs and hiring

- [LinkedIn Jobs Scraper](https://apify.com/aurelix/linkedin-jobs) - LinkedIn job postings by keyword, country and date posted, with no login: title, company, location, salary where shown, seniority and description. Why this one: exact country filter and filtered-out jobs free; 25% under the most-used LinkedIn scraper. Example: [linkedin-jobs-example](https://github.com/Aurelix-Solutions/linkedin-jobs-example).
- [Greenhouse Jobs Scraper](https://apify.com/aurelix/greenhouse-jobs-scraper) - Jobs straight from company career sites on Greenhouse, Lever, Ashby and SmartRecruiters, in one schema with salary, remote flag and apply link. Why this one: 8x cheaper than the leading jobs API and 40% under the leading feed, read live from each employer's board. Example: [career-site-jobs-example](https://github.com/Aurelix-Solutions/career-site-jobs-example).

## E-commerce and product research

- [Amazon Best Sellers Scraper](https://apify.com/aurelix/amazon-best-sellers) - Amazon Best Sellers and New Releases by category in 10 marketplaces (US, UK, DE, FR, IT, ES, CA, AU, IN, JP): rank, ASIN, price, rating and reviews, plus rank changes since your last run. Why this one: 69% under the most-used Best Sellers scraper ($1.80 vs $5.90 per 1,000), 10 marketplaces incl. amazon.ca. Example: [amazon-best-sellers-example](https://github.com/Aurelix-Solutions/amazon-best-sellers-example).
- [AliExpress Scraper](https://apify.com/aurelix/aliexpress-product-search) - AliExpress search results for any keyword: price, original price, discount, rating, units sold and ship-from country. Why this one: cheapest of the three we compared ($1.80 vs $2.49-$9.00 per 1,000), sponsored results flagged. Example: [aliexpress-product-search-example](https://github.com/Aurelix-Solutions/aliexpress-product-search-example).

## Leads and local business

- [Google Maps Business Scraper](https://apify.com/aurelix/google-maps-scraper) - Google Maps business listings by keyword and city: categories, address, phone, website, rating, hours and coordinates. No review text. Why this one: $1.50 per 1,000 places, less than half the leading Google Maps scrapers ($4-5), with many cities per run and an only-new-places mode. Example: [google-maps-businesses-example](https://github.com/Aurelix-Solutions/google-maps-businesses-example).

## Public records

- [Canada Building Permits Scraper](https://apify.com/aurelix/canada-building-permits-scraper) - Development applications and building permits from seven Canadian cities' open data: address, ward, type, status and value. No owner names. Why this one: the only one with development applications and a ward filter, and the cheapest of the three ($3.00 vs $3.50-$5.00). Example: [canada-development-applications-example](https://github.com/Aurelix-Solutions/canada-development-applications-example).

## Marketing and SEO research

- [Google Trends Scraper](https://apify.com/aurelix/google-trends-scraper) - Google Trends for any number of keywords on one 0-100 scale: interest over time, interest by country, state, metro or city, and top and rising related queries. Why this one: $1.50 per 1,000 results vs $3.00 plus platform usage for Apify's own Google Trends Scraper, and it accepts Google Trends explore links. Example: [google-trends-example](https://github.com/Aurelix-Solutions/google-trends-example).

## Licence

This list is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The tools it links to are separate paid services on the Apify Store.
