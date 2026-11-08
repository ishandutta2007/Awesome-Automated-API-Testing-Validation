# Awesome-Automated-API-Testing-Validation

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **several entries in your list have no usable pricing**, and two tools are not primarily API testing frameworks.

## The data problems

**Cypress is a browser E2E testing framework, not an API testing tool.** It can make HTTP requests via `cy.request()`, but its core value is UI testing. The 2026 changelog is entirely about component testing (Angular 21+, Vite 8+, Next.js 15+), HTTP/2/3 support, and Electron deprecation . **Do not list it as an API testing framework**—it belongs in a browser testing list.

**Playwright is a browser automation framework, not an API testing tool.** Its 2026 releases focus on ARIA snapshots, locator assertions, and browser versions . It has `APIRequestContext` for API calls, but that is a supporting feature, not the product's purpose.

**BlazeMeter and Testim surfaced no pricing.** Do not fabricate.

**Katalon's "Studio Enterprise" and "True Automation" are different products at different price points.** Studio Enterprise is **$229/seat/month** ($1,000/seat/year for first 3 seats, $2,199/year from 4th seat). True Automation is **$142–$167/seat/month** ($1,699–$2,000/seat/year), which *includes* True Platform plus Studio Enterprise authoring . **Do not conflate them.**

## What the search results actually contain

| Tool | License / Pricing | Verified detail |
|---|---|---|
| **Karate** | Open source | v2.1.1 (July 2026); fixes for `karate.match()`, JSON path, call/callonce scoping, Gatling logging; HTML report faster on large features  |
| **REST Assured** | Open source | 6.3.0 (Oct 2026) prepares for 7.0; Java-only since 6.2 (Groovy dependency dropped); mutual TLS, JSON Schema draft 2020-12 support  |
| **ReadyAPI** | **$1,170** (SmartBear store)  | Functional, security, load testing in CI/CD; Virtualization base is free with any ReadyAPI license  |
| **Postman** | **Free**; paid plans; **Monitoring $20 per 50,000 requests/team/month**; **AI credits $0.05–$0.035/credit**; **Playwright integration $0.04/VuH**  | Monitoring, AI credits, Flows credits are usage-based add-ons  |
| **Katalon** | **Studio Enterprise $229/seat/mo**; **True Automation $142–$167/seat/mo**; **True Platform $59/seat/mo**  | True Automation includes Studio Enterprise authoring + AI self-healing + web/API/mobile/desktop  |

**Open-source projects (usable):**
- **Karate** (v2.1.1, July 2026) 
- **REST Assured** (6.3.0, Oct 2026) 

**What is missing:**
- **No star counts** for Karate or REST Assured in the results.
- **No pricing** for BlazeMeter or Testim.
- **No pricing** for Tavern (open source, but no release info surfaced).
- **No revenue or valuation** for any vendor.

## What I recommend

**Remove Cypress and Playwright** from the API testing list. They are browser testing frameworks. If you want to keep them, mention `cy.request()` and `APIRequestContext` as *supporting features*, not core products. Cite their 2026 release notes as evidence of their actual focus .

**The open-source section is genuinely strong:** Karate and REST Assured are both mature, actively released in 2026, and have verified recent changes . **Do not invent star counts**—none were surfaced.

**The SaaS section has vendor-confirmed pricing for ReadyAPI ($1,170), Postman (usage-based add-ons), and Katalon (multiple tiers).** Mark BlazeMeter and Testim as **"pricing not surfaced."**

**Flag the Katalon tier confusion explicitly:** Studio Enterprise ($229/seat/mo) is the authoring tool; True Automation ($142–$167/seat/mo) *includes* Studio Enterprise plus platform and AI features. A reader comparing them needs that context .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, present Cypress/Playwright as API testing tools, or conflate Katalon's Studio Enterprise with True Automation.
