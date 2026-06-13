# The Guardian (guardian)

The Guardian newspaper REST API providing access to 2M+ articles, news content, sections, tags, editions, and real-time breaking news from Guardian journalists worldwide.

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- News
- Media
- Content
- Articles
- Journalism

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### The Guardian Content API

Search and retrieve articles, news content, and multimedia from The Guardian's archive of over 2 million pieces of content published since 1999. Supports keyword search, section filtering, tag filtering, date range queries, and retrieval of full article body text with metadata.

**Base URL:** `https://content.guardianapis.com/`

#### Endpoints

- `GET /search` — Search articles by keywords and filters
- `GET /sections` — List all available news sections (75+)
- `GET /tags` — List all article classification tags
- `GET /editions` — List editions (UK, US, Australia)
- `GET /{articleId}` — Retrieve a specific article by ID

#### Tags

- News
- Articles
- Content
- Search

#### Properties

- [Documentation](https://open-platform.theguardian.com/documentation/)
- [Registration](https://open-platform.theguardian.com/access/)
- [Plans](plans/guardian-plans-pricing.yml)
- [Rate Limits](rate-limits/guardian-rate-limits.yml)
- [FinOps](finops/guardian-finops.yml)
