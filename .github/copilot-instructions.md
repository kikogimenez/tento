# GitHub Copilot Instructions

## Project

Tento is building the intelligence infrastructure for the next generation of restaurants in Latin America.

Tento connects restaurant channels — Quick Service, Reservations, Delivery, Loyalty and CRM — into a unified data platform. On top of that platform, the Restaurant Brain transforms customer and operational data into insights, predictions, recommendations and automated decisions executed by AI agents.

The strategic asset is the combination of:

- A proprietary restaurant dataset.
- The Restaurant Brain that continuously learns from restaurant-customer interactions.

The long-term vision is to replace intuition with intelligence across the Latin American restaurant industry.

## Brand

Use the official brand manual as reference:

`ai-context/00_tento_Manual_de_Marca_compressed.pdf`

Use the official logos located in:

`ai-context/logos/`

## Design reference

Official website:

https://www.tento.la

Official Figma:

https://www.figma.com/design/RSWKkWHZmpLHR5R4jkDgzc/Tento?node-id=102-4103&t=YhPPJet9TDpbbuDR-1

Use the website, Figma and brand manual as the source of truth for UI and UX decisions.

Maintain the same design language:

- Premium
- Minimalist
- Clean
- B2B SaaS
- Mobile-first
- Rounded components
- Clear typography
- Strong spacing
- Modern restaurant-tech aesthetic

## Product modules

Current and planned modules include:

- Quick Service QR ordering
- Dine-in QR ordering and payment
- Delivery and takeaway
- Reservations
- Loyalty
- CRM and customer data
- Data Platform
- Restaurant Brain
- Marketing automation
- AI agents for restaurant operations and commercial execution
- Fintech services on the roadmap

## Product maturity

Respect the following maturity levels:

- Software: operational.
- Data Platform: operational.
- Restaurant Brain: operational.
- AI Agents: in development.
- Fintech: roadmap.

Do not present planned capabilities as currently live.

## Development guidance

When generating UI:

- Follow the visual style of tento.la and the official Figma.
- Prioritize clean layouts and strong visual hierarchy.
- Use reusable components.
- Keep interfaces simple, intuitive and operational.
- Avoid unnecessary visual complexity.
- Design for restaurant owners, operators, chains and their customers.

When generating copy:

- Use clear, professional Spanish unless another language is requested.
- Keep wording direct, credible and commercially strong.
- Avoid unsupported claims and inflated language.
- Speak to restaurant owners, operators, chains, partners and investors according to the context.

When generating product features:

- Optimize for restaurant operations.
- Prioritize speed, reliability and ease of use.
- Consider integrations with POS, payments and logistics.
- Preserve the unified data model and customer identity.
- Explain how features contribute to sales, recurrence, efficiency or profitability.

## Investor material

The primary source of truth for investor-facing content is:

`ai-context/investors/company-story.md`

The current official Executive Summary is:

`ai-context/investors/Tento_Resumen_Ejecutivo.docx`

Use `company-story.md` for:

- Narrative
- Positioning
- Vision
- Problem
- Solution
- Strategic assets
- Product maturity
- Market
- Traction
- Metrics
- Business model
- International expansion
- Competitive advantages
- Partners

Use the Executive Summary as the original supporting document and as a reference for visual hierarchy.

Only use the following reference when the file actually exists:

`ai-context/investors/onepager.pdf`

When generating:

- Executive summaries
- One-pagers
- Pitch decks
- Investor presentations
- Fundraising documents

follow these rules:

1. Treat `company-story.md` as the primary source of truth.
2. Do not invent or extrapolate metrics, customers, partners or capabilities.
3. Preserve the distinction between operational products, products in development and roadmap.
4. Use the latest figures documented in `company-story.md`.
5. Maintain consistency with the official brand manual, website and Figma.
6. Use concise, credible language suitable for Latin American venture capital investors.

## Current key facts

Use these figures unless a newer approved document replaces them:

- 70 active restaurant clients.
- 62 Tostado locations in implementation.
- 15 Goût locations in implementation.
- 10 Grupo Devoto locations in implementation.
- Growth of approximately 15 new locations per month.
- USD 50 current SaaS ARPU in Argentina.
- 1.5% churn, with zero churn in the last two months.
- Approximately USD 5K monthly burn.
- Close to break-even.
- 2.5 million restaurants in Latin America.
- Five-year objective: more than 40,000 restaurants.
- Required market penetration: approximately 1.6%.

## Validation case: Tostado Café Club

Approved facts:

- Framework agreement covering 62 locations.
- Approximately 40% of in-person orders processed through Tento.
- Approximately 30% higher average ticket for digital orders.
- Approximately 30% reduction in cashier requirements.
- 1,463 unique customers identified in 47 days.
- 25 customers at churn risk detected automatically.
- ARS 828,488 in monthly revenue at risk identified.

## Confidentiality and accuracy

- Treat investor materials as confidential business context even when stored in this public repository.
- Do not expose sensitive information unless the requested output requires it.
- Prefer accuracy over persuasion.
- When sources conflict, use `ai-context/investors/company-story.md`.
