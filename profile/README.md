# TidyHarvest

Pay-per-result web data tools on the [Apify Store](https://apify.com/tidyharvest): events, jobs, ad
libraries, Google Maps, app stores, prediction markets, and science and government data, as clean rows
you can drop into a spreadsheet, a database or an AI agent. You pay per result, with no subscription,
and every filter and cap applies before a row is charged.

Built and maintained by [Jonathan Chong](https://jchong.dev). Several of these tools also feed
[What's Up In](https://whatsupin.ai), free event calendars for 57 cities.

**Open source:** five of the simpler actors (Hacker News, Wikipedia, Federal Register,
ClinicalTrials.gov, GitHub) are MIT-licensed in [tidyharvest/open-actors](https://github.com/tidyharvest/open-actors).

## Catalog (55 actors)

### Events and venues

- **[Luma Events Scraper: Every Event in Any City (lu.ma)](https://apify.com/tidyharvest/luma-events-scraper)**: Every public Luma (lu.ma) event in any city, calendar or link: dates, venue and coordinates, hosts with social links, RSVPs, ticket tiers, descriptions.
- **[Eventbrite Events Scraper: Any City, Any Day](https://apify.com/tidyharvest/eventbrite-day)**: Every Eventbrite event in a city on any day (or by keyword/category), with price range, venue and coordinates, organizer and category.
- **[Eventbrite Organizer Scraper](https://apify.com/tidyharvest/eventbrite-organizer-scraper)**: Eventbrite organizer profiles (website, social links, followers, events hosted) plus their upcoming and past events with venue, coordinates, prices and category.
- **[Meetup Events Scraper: City, Keyword, Group & Date](https://apify.com/tidyharvest/meetup-events-scraper)**: Get Meetup events for any city or coordinates and radius, keyword, category, date range or group: title, start/end with time zone, venue address and coordinates, online/hybrid flag, group, RSVP count, fee, topics, image and description.
- **[Partiful Events Scraper: Explore, Event & Host Events](https://apify.com/tidyharvest/partiful-events-scraper)**: Public Partiful events from city Explore pages (SF, NYC, LA, Boston, DC, Chicago, Austin, Miami, London), event URLs or host profiles: time and timezone, venue, address, coordinates, hosts, price, capacity, RSVP state.
- **[Resident Advisor Events Scraper](https://apify.com/tidyharvest/resident-advisor-events-scraper)**: Resident Advisor (RA.co) events by city, club, promoter, DJ or URL: date and times, venue address and coordinates, lineup, genres, cost, RA ticket prices, attending count, promoters, flyers.
- **[Facebook Pages Scraper: Posts & Upcoming Events](https://apify.com/tidyharvest/facebook-pages-scraper)**: Upcoming events (date, venue, address, ticket link, description, hosts) and the latest post from any public Facebook page, logged out with no account.
- **[Eventective Scraper: Event Venues, Capacity & Prices](https://apify.com/tidyharvest/eventective-scraper)**: Get event and wedding venues, meeting rooms and vendors (caterers, DJs, photographers) from Eventective for any US or Canadian city: address, coordinates, capacity, price ranges, packages, amenities, photos, website and phone.
- **[The Vendry Venues Scraper: Event Spaces by City](https://apify.com/tidyharvest/vendry-venues-scraper)**: Every event venue The Vendry lists for a city, with capacity per room, address and coordinates, website, phone, booking link and pricing notes.

### Local businesses, companies and leads

- **[Google Maps Scraper Pro: Reviews, Photos & Emails](https://apify.com/tidyharvest/google-maps-scraper-pro)**: Google Maps places with reviews, star breakdown, popular times, review topics, photos and emails.
- **[Google Maps Places Scraper: Businesses, Phones & Websites](https://apify.com/tidyharvest/google-maps-places-scraper)**: Google Maps businesses for any search and city: structured address, phone, website, rating, hours, closed and unclaimed flags.
- **[Website Contacts Scraper: Emails, Phones, Socials](https://apify.com/tidyharvest/website-contacts-scraper)**: Emails, phone numbers, social profiles and addresses from any list of company websites.
- **[Company Lookup: Website, LEI, Ticker and Profile](https://apify.com/tidyharvest/company-lookup)**: Turn a company name, domain, LEI or Wikidata id into a profile: official website, ticker, industry, HQ, size, social handles and GLEIF legal entity with parents.
- **[Domain WHOIS (RDAP) & DNS Lookup](https://apify.com/tidyharvest/domain-whois-dns-lookup)**: Bulk domain WHOIS & DNS: registrar, created/expiry dates, age, availability, owner organization and country, MX, email provider, SPF, DMARC, DKIM.
- **[NPI Registry Scraper: US Doctors & Healthcare Providers](https://apify.com/tidyharvest/npi-registry-scraper)**: Build lists of US doctors, dentists, clinics and pharmacies from the official CMS NPI Registry: NPI, name, credential, specialty and license, practice address, phone, fax and Direct addresses.
- **[Y Combinator Companies Scraper: YC Startups, Founders & Jobs](https://apify.com/tidyharvest/yc-companies-scraper)**: All 6,300 Y Combinator companies with founders (LinkedIn, bio, email), year founded, socials, news and open jobs.

### Ads, SEO and the web

- **[Meta Ad Library Scraper: Cheap Facebook Ads](https://apify.com/tidyharvest/meta-ad-library-scraper)**: Facebook and Instagram ads from the Meta Ad Library by page, keyword or ad link, at a low all-in price.
- **[Facebook Ads Library Scraper](https://apify.com/tidyharvest/facebook-ads-library-scraper)**: Meta Ad Library ads by page, keyword or link: text, media, dates, platforms, political spend, EU/UK reach included free.
- **[Google Ads Transparency Scraper](https://apify.com/tidyharvest/ads-transparency-scraper)**: Google Ads Transparency Center ads by advertiser or domain: ad copy (text ads read from images), formats, landing pages and EU impressions.
- **[Sitemap URL Extractor: All Pages, Lastmod & Status](https://apify.com/tidyharvest/sitemap-urls-extractor)**: Get every page URL from a website's sitemaps with lastmod dates, hreflang alternates, Google News titles and optional HTTP status checks.
- **[Wayback Machine Scraper: Archived Snapshots & Pages](https://apify.com/tidyharvest/wayback-machine-scraper)**: List Internet Archive Wayback Machine snapshots for URLs or whole domains (date range, status, MIME, collapse by change/day/URL), get the closest capture to a date, and optionally download archived page text or HTML.

### Jobs and employers

- **[Recent Jobs Scraper: Indeed & LinkedIn](https://apify.com/tidyharvest/recent-jobs-scraper-indeed-linkedin)**: Fresh Indeed or LinkedIn jobs for any search and city, posted in the last hours or days, with full descriptions and pay ranges.
- **[Career Page Jobs Scraper: Greenhouse, Lever, Ashby, Workable](https://apify.com/tidyharvest/ats-jobs-scraper)**: Get every open job from a company's own careers page with salary ranges, remote flags, posting dates and full descriptions.
- **[Workday Jobs Scraper: Any Company Career Site](https://apify.com/tidyharvest/workday-jobs-scraper)**: Fresh jobs from any Workday career site (NVIDIA, Salesforce, Adobe and thousands more) with full descriptions.
- **[Remote Jobs Scraper: Remote OK, Jobicy & Himalayas](https://apify.com/tidyharvest/remote-jobs-aggregator)**: Remote jobs from three major remote-work job boards in one run: salary, location rules, tags and full descriptions.
- **[Hacker News 'Who is Hiring' Scraper](https://apify.com/tidyharvest/hacker-news-who-is-hiring-scraper)**: Every job post from Hacker News 'Ask HN: Who is hiring?' for any month, with company, remote/onsite, visa flags and full text.
- **[Indeed Reviews Scraper](https://apify.com/tidyharvest/indeed-reviews-scraper)**: Indeed employee reviews for any company: stars and five sub-ratings, text, pros, cons, reviewer job title and location, employer reply.

### News, social and communities

- **[Google News Scraper: Search, Topics, Any Country](https://apify.com/tidyharvest/google-news-scraper)**: Google News articles for any search, topic or section, any language and country: headline, original article URL, publisher, date, related coverage, plus description and image on request.
- **[RSS Feed Reader: RSS, Atom & JSON Feed to JSON](https://apify.com/tidyharvest/rss-feed-reader)**: Turn RSS, Atom, RDF and JSON feeds (or any website with a feed) into uniform JSON: titles, links, ISO dates, authors, content, enclosures.
- **[Substack Scraper: Posts & Newsletters](https://apify.com/tidyharvest/substack-scraper)**: Scrape posts from any Substack newsletter (subdomain or custom domain): titles, dates, authors, likes, comments, restacks, tags, paid/free status and full text of free posts.
- **[Medium Articles Scraper: Tags, Authors, Publications](https://apify.com/tidyharvest/medium-articles-scraper)**: Latest Medium articles by tag, author, publication (custom domains too) or article URL, with full text and HTML, word count, reading time, tags, image and date, plus date/keyword filters.
- **[Hacker News Search Scraper](https://apify.com/tidyharvest/hacker-news-search-scraper)**: Search Hacker News stories, comments, Ask HN and Show HN by keyword, author, thread, points and date, or grab the current front page. · [source](https://github.com/tidyharvest/open-actors/tree/main/hacker_news_search_scraper)
- **[Bluesky Posts & Profile Scraper](https://apify.com/tidyharvest/bluesky-posts-scraper)**: Export Bluesky posts by keyword search or from any profile, custom feed, list or post thread: text, likes, reposts, replies, quotes, hashtags, links, images and quoted posts, plus free profile rows with follower counts.
- **[Mastodon Posts Scraper: Hashtags, Accounts, Trending, Threads](https://apify.com/tidyharvest/mastodon-scraper)**: Scrape public Mastodon posts by hashtag, account, trending, local timeline or thread: text, author, engagement counts, tags, media and link previews.
- **[Telegram Channel Scraper: Posts, Views, Reactions & Media](https://apify.com/tidyharvest/telegram-channel-posts-scraper)**: Scrape any public Telegram channel: post text, dates, view counts, emoji reactions, forwards, photos, videos, links, hashtags and subscriber counts.
- **[YouTube Comments Scraper](https://apify.com/tidyharvest/youtube-comments-scraper)**: Export comments and replies from any public YouTube video or Short: text, author, likes, dates, pinned and hearted flags, date and keyword filters.
- **[Podcast Scraper: Apple Podcasts Search, Charts & RSS Episodes](https://apify.com/tidyharvest/podcast-scraper)**: Search Apple Podcasts, look up shows by link or id, or pull the Top Shows chart per country; get publisher, feed URL, genres, rating and the newest episodes with audio URLs, durations and descriptions.
- **[Stack Overflow & Stack Exchange Scraper](https://apify.com/tidyharvest/stack-overflow-questions-scraper)**: Search Stack Overflow and any Stack Exchange site by keyword, tag, score and date, browse a tag, or paste question URLs from any site.

### Apps, stores and developer data

- **[App Store Scraper: Apple Apps, Search & Top Charts](https://apify.com/tidyharvest/appstore-apps-scraper)**: Search the Apple App Store by keyword in any country, look up apps by id, bundle id or URL, list a developer's apps or pull top charts: price, ratings, version, dates, size, screenshots.
- **[App Store Reviews Scraper](https://apify.com/tidyharvest/appstore-reviews-scraper)**: Apple App Store reviews for any app, in many countries per run: stars, title, text, dates and developer responses.
- **[Steam Reviews Scraper](https://apify.com/tidyharvest/steam-reviews-scraper)**: Export Steam user reviews for any game: review text, recommended or not, language, dates, votes, playtime at review, reviewer stats, developer replies and the game's review score.
- **[Shopify Products Scraper](https://apify.com/tidyharvest/shopify-products-scraper)**: Scrape products from any Shopify store, collection or product URL: prices, compare-at and sale flag, variants with SKU and availability, optional stock counts and barcodes, images, tags, vendor, currency.
- **[Chrome Web Store Scraper: Extensions, Users & Ratings](https://apify.com/tidyharvest/chrome-web-store-scraper)**: Chrome Web Store extensions by keyword search (store order, with rank), URL/ID, category, collection or name keyword: users, rating, version, last updated, publisher name/website, badges, manifest permissions, privacy practices, screenshots.
- **[GitHub Repository Scraper](https://apify.com/tidyharvest/github-repos-scraper)**: Search GitHub repositories with any qualifiers or look up specific repos: stars, forks, topics, language, license, dates, optional README and language breakdown. · [source](https://github.com/tidyharvest/open-actors/tree/main/github_repos_scraper)

### Markets and finance

- **[Polymarket Scraper: Prediction Market Odds & Prices](https://apify.com/tidyharvest/polymarket-scraper)**: Live Polymarket odds by keyword, tag or URL: outcome prices and probabilities, 24h/total volume, liquidity, end date, resolution and winner, optional price history and a free order book.
- **[Kalshi Scraper: Prediction Market Odds & Prices](https://apify.com/tidyharvest/kalshi-scraper)**: Live Kalshi odds by keyword, category, series, event or ticker: YES/NO bid/ask, implied probability, 24h/total volume, open interest, close time, status and result, optional candlestick history and a free order book.
- **[Yahoo Finance Scraper: Stock Prices, History & Dividends](https://apify.com/tidyharvest/yahoo-finance-scraper)**: Yahoo Finance prices for any ticker (stocks, ETFs, indices, crypto, forex): one summary row with price, 52-week range, returns, moving averages and dividend yield, or OHLCV candles from 1 minute to monthly, plus symbol search and news.
- **[SEC Insider Trading Scraper: Form 4 Buys & Sells](https://apify.com/tidyharvest/sec-insider-trading-scraper)**: Track insider buying and selling from official SEC Form 4 filings: insider name and role, open-market purchase or sale, shares, price, dollar value and 10b5-1 flag.

### Government, science and reference

- **[Federal Register Scraper: Rules, Notices & Executive Orders](https://apify.com/tidyharvest/federal-register-scraper)**: Pull US Federal Register documents for one or many search terms: final and proposed rules, notices and executive orders with agencies, effective dates, comment deadlines, dockets, RINs, CFR parts, full text and PDF links. · [source](https://github.com/tidyharvest/open-actors/tree/main/federal_register_scraper)
- **[USAspending Federal Contracts & Grants Scraper](https://apify.com/tidyharvest/usaspending-awards-scraper)**: Find who wins federal contracts, grants and loans: recipient company, UEI, address, award amount, agency, dates, NAICS/PSC codes and place of performance from the official USAspending.gov API.
- **[ClinicalTrials.gov Scraper: Clinical Trials Search & Export](https://apify.com/tidyharvest/clinicaltrials-scraper)**: Search and export clinical trials from ClinicalTrials.gov by condition, drug, sponsor, location, phase, status, age, sex and funder: NCT id, titles, status, phases, sponsor, enrollment, dates, sites, eligibility and outcomes. · [source](https://github.com/tidyharvest/open-actors/tree/main/clinicaltrials_scraper)
- **[OpenAlex Scholarly Works Scraper: Papers, Citations, Abstracts](https://apify.com/tidyharvest/openalex-papers-scraper)**: Search 250M+ research papers in OpenAlex: many keyword searches per run, or by author, institution or DOI.
- **[arXiv Papers Scraper: Search Papers, Abstracts & Authors](https://apify.com/tidyharvest/arxiv-papers-scraper)**: Run one or many arXiv searches by keywords, category, author, date range or ID and get titles, abstracts, authors, categories, dates, DOIs and PDF links from the official arXiv API.
- **[Google Patents Scraper: Search, Claims & Citations](https://apify.com/tidyharvest/google-patents-scraper)**: Search Google Patents (USPTO, EPO, WIPO, CN, JP, KR, 100+ offices) by keyword, assignee, inventor, CPC, country and date, or look up patent numbers: abstract, claims, CPC, citations, cited-by, family, legal events, expiry, PDF.
- **[Wikipedia Scraper: Articles, Search & Pageviews](https://apify.com/tidyharvest/wikipedia-scraper)**: Run many Wikipedia searches at once in any language, or pull articles by title, link or category, or the day's most-viewed: summary, full text, categories, Wikidata ID, coordinates and daily pageviews. · [source](https://github.com/tidyharvest/open-actors/tree/main/wikipedia_scraper)


Prices, input options and sample output are on each Store page. Questions or a source you'd like covered: open an issue on [open-actors](https://github.com/tidyharvest/open-actors/issues) or email [jon@jchong.dev](mailto:jon@jchong.dev).
