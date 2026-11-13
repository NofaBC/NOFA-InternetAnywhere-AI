# NOFA InternetAnywhere AI™ — Interactive Showroom Prototype

**Status:** Interactive concept / interest-validation demo. **Not a live eSIM or internet access service.**

## Purpose
A single-page, mobile-responsive demonstration of a future NOFA AI Factory product that could help users purchase and activate cellular data plans through authorized eSIM telecom partners. The purpose is to gauge demand before investing in connectivity infrastructure.

## Features
- Responsive marketing site and illustrated phone preview.
- Destination selection (demonstration only).
- Sample 5/10/20 GB data plans, hypothetical prices and one-time vs monthly concept switch.
- Clear warnings: no live internet, no checkout, no coverage guarantees.
- Interest form which opens the visitor's email client, prefilled to `nofabusinessconsulting@gmail.com`.

## Deployment
Deploy `index.html` directly to Vercel, Netlify, or any static web host. There are no dependencies, API keys, or backend services. For Vercel, create a repository with `index.html` in its root and import the repository as a static project; no build command is needed.

## Measuring interest
The current interest form uses `mailto:`. **A visitor must send the email manually.** This method avoids collecting private information on a server but may have lower completion rates if they do not have a configured email application.

For reliable aggregate interest measurements in a later version, connect a hosted form or secure backend (with consent, privacy notice, spam protection, and storage policy). Do not infer demand from page views alone; distinguish page visits, genuine inquiries, and requests for paid service.

## Production requirements (not implemented)
- eSIM-capable device validation, appropriate activation flow and supported countries.
- Authorized wholesale partner and verified plan prices, coverage, terms, and reseller rights.
- Secure payment processing, refunds, fraud prevention and customer support.
- Regulatory/privacy/compliance review, including applicable telecom obligations.
- Real eSIM order and provisioning APIs, data-usage tracking and subscription management.

## Suggested showroom label
**InternetAnywhere AI™** — *Concept Prototype / Gauging Interest*

**Description:** Explore an envisioned mobile-internet app that helps travelers and businesses find and activate data plans through participating eSIM providers. This interactive demonstration does not sell or activate internet service. Tell NOFA what you would want from a future version.

**NOFA AI Factory:** https://nofaaifactory.com
