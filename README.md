# Eleczo V2: AI Tools for Sales & Engineering

A set of standalone AI-powered tools built on a live product catalog and Anthropic Claude models, deployed together as a Dockerized stack.

> Showcase repository. The source code is private; this README describes the architecture and my contribution.

## Tech stack

Node.js · Express · React · PostgreSQL · Redis · Meilisearch · nginx · Docker · Anthropic Claude · Magento GraphQL

## Tools

### Product Search and BOM Matching
- Natural-language product search over the live catalog.
- **BOM-to-part matcher:** upload a customer BOM (PDF, Excel, CSV, or image, up to 25 MB) and get each line matched to part numbers with descriptions, rates, discounts, and links. Results export to Excel.
- Cross-brand equivalent finder.
- Image-to-part-number extractor.

### WhatsApp Reply Generator and Email Composer
- Drafts context-aware sales and support messages.
- Reusable email template library.

## Deployment

All services run as Docker containers behind nginx: React frontend, Express API, PostgreSQL, Redis, and Meilisearch.

## Screenshots

_Add screenshots here with all customer and pricing data blurred or replaced by dummy data._

