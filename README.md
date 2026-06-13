# Alchemer

Enterprise survey and experience management platform with a REST API for managing surveys, accessing response data, managing contacts, and automating survey workflows.

**Website:** https://www.alchemer.com  
**API Docs:** https://apihelp.alchemer.com/help  
**Developer Home:** https://developer.alchemer.com/help  
**Status:** https://alchemer.statuspage.io/  

## API

The Alchemer REST API v5 provides programmatic access to surveys, responses, contacts, campaigns, and account management. API access is available exclusively on Business Platform accounts.

**Base URL (US):** `https://api.alchemer.com/v5`  
**Auth:** API Key + Secret, or OAuth 1.0  
**Rate Limit:** 240 requests/minute (account-level)  
**Regions:** US, EU (`.eu`), Canada (`-ca.com`), Australia (`app.au.alchemer.com`)  

## Resources

- [apis.yml](apis.yml) — APIs.json 0.19 provider profile
- [plans/alchemer-plans-pricing.yml](plans/alchemer-plans-pricing.yml) — Pricing tiers and features
- [rate-limits/alchemer-rate-limits.yml](rate-limits/alchemer-rate-limits.yml) — Rate limit details
- [finops/alchemer-finops.yml](finops/alchemer-finops.yml) — FinOps cost guidance
