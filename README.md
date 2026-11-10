# Donkin.ai — Data Pipeline Engineering (Project Showcase)

**Role:** Data Developer Intern, Zeuspace Group · May–August 2025  
**Focus:** Near-real-time data ingestion, data quality, and relational data modeling  
**Technologies used:** Python, `asyncio`, `aiohttp`, REST APIs, PostgreSQL, Docker

> **Portfolio overview, not the production repository.** This page summarizes my contributions during an internship. It does not contain proprietary source code, datasets, credentials, or internal infrastructure details. This is an independent portfolio description, not an official Zeuspace or Donkin.ai repository.

## Project overview

I worked on backend data infrastructure supporting a cryptocurrency market and community monitoring platform. The work involved integrating information from multiple external sources and organizing noisy, frequently updated records for downstream analytics. The platform monitored approximately **500 tokens**, with market-data updates on the order of **30–60 seconds**.

## My contributions

### Concurrent data ingestion
- Developed Python ingestion components for market information obtained through external APIs and publicly accessible community data sources.
- Used asynchronous requests and concurrent processing to handle multiple upstream sources and recurring collection cycles.
- Implemented rate-limit handling, retries, and error logging to improve resilience to transient failures.

### Data quality and consistency
- Applied deduplication and timestamp normalization to reconcile records from heterogeneous sources.
- Supported validation and cleaning workflows for continuously refreshed market and community metrics.

### Database design
- Contributed to PostgreSQL relational schema design, including structured records for token metadata, market indicators, liquidity, and community metrics.
- Used normalized tables and indexes to support consistent storage and efficient downstream querying.

## Engineering considerations

| Challenge | Approach |
| --- | --- |
| Multiple upstream sources | Asynchronous API ingestion and consistent processing interfaces |
| Rate limits and transient errors | Retry handling and diagnostic logging |
| Duplicated or inconsistent records | Deduplication, timestamp normalization, and validation |
| Repeated analytical queries | Structured PostgreSQL schemas and indexes |

## Scope and attribution

This was **team-based internship work**. The bullets above describe the areas I contributed to; they should not be read as a claim that I alone designed or built the entire platform. Numerical figures are approximate descriptions of project scope, not independently benchmarked performance claims.

## Source-code availability

The original work was developed in a commercial context and **is not distributed here**. This showcase intentionally does not mirror or link to a private code repository. Any future illustrative example will be independently written using synthetic data and only added if appropriate to share.

## Contact

For academic or professional inquiries, please contact me through my [GitHub profile](https://github.com/Y237cui).
