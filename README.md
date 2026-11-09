# Awesome-Automated-API-Testing-Validation
# Awesome-Automated-API-Testing-Validation

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **Cypress and Playwright are not API testing tools**, and **Dredd is archived and unmaintained**.

## The data problems

**Cypress and Playwright are browser testing frameworks, not API testing tools.** They can make HTTP requests (`cy.request()` and `APIRequestContext`), but that is a supporting feature. Their core value is UI automation. Listing them as API testing platforms misleads readers. The search results for this query returned no information about either tool's API testing capabilities—only unrelated results.

**Dredd is archived and unmaintained.** The project has been **archived and unmaintained since November 2024**; the last release, 14.1.0, shipped in **November 2021** . It validates API implementations against API Blueprint or OpenAPI documents , but **do not present it as an active, recommended tool**. If you list it, mark it clearly as archived.

**BlazeMeter and Testim pricing surfaced partially.** BlazeMeter APIs: **Small $79/month (250K requests, 5 team members), Medium $199/month (1M requests, 40 members), Large $599/month (5M requests, 50 members)** . Testim (Tricentis) starting at **$450/month** per Software Advice .

## What the search results actually contain

**SaaS pricing (usable):**

| Platform | Entry pricing | Verified detail |
|---|---|---|
| **Postman** | Usage-based add-ons: **Monitoring $20/50K requests/team/month**; **AI credits $0.05–$0.035/credit**; **Performance testing $0.04/VuH**; **Flows $1/1,000 credits**  | Free, Solo, Team, Enterprise per-user plans |
| **BlazeMeter** | **Small $79/mo** (250K requests); **Medium $199** (1M); **Large $599** (5M)  | API Monitoring & Functional Testing included |
| **ReadyAPI** | **LoadUI NG Pro renewal: $21,647.99 for 2 years** (1 fixed user)  | This is a load testing renewal, not the core API testing price |
| **Katalon** | **Studio Enterprise $229/seat/month**; **True Automation $142–$167/seat/month** (first 3 seats, promo)  | True Automation includes Studio Enterprise authoring |
| **Testim** | **From $450/month**  | Third-party listing, not vendor-published |

**Open-source projects (usable):**

| Project | Stars | What it actually does |
|---|---|---|
| **Karate** | **8,977+**  | REST, GraphQL, SOAP, mocks, parallel execution, performance testing; MIT; 2M+ monthly downloads  |
| **Schemathesis** | **2,529**  | Property-based testing from OpenAPI/GraphQL schemas; automatically generates test cases, finds crashes and spec violations; works as CLI, Python library, or pytest plugin  |
| **Tavern** | Not surfaced | Pytest plugin and Python library for API testing with YAML syntax; supports REST and MQTT; access to full pytest ecosystem  |
| **REST Assured** | Not surfaced | Java DSL for REST API testing; integrates with TestNG/JUnit, Maven/Gradle  |

**What is missing:**
- **No pricing** for Postman's base plans, ReadyAPI's core API testing (only the LoadUI NG renewal surfaced), or Karate's paid tiers.
- **No star counts** for Tavern or REST Assured.
- **No information** on Cypress or Playwright API testing capabilities—the results did not contain any.

## What I recommend

**Remove Cypress and Playwright** from the API testing list. If you must mention them, note they are browser testing frameworks with HTTP request support, not API testing platforms.

**Mark Dredd as archived** (last release 2021, unmaintained since November 2024) . Do not list it as an active recommendation.

**The open-source section is genuinely strong:** Karate (8,977+ stars, MIT, 2M+ downloads) , Schemathesis (2,529 stars, property-based fuzzing) , Tavern (pytest plugin, YAML syntax) , and REST Assured (Java DSL)  are all real, active, and well-documented.

**Flag the pricing model differences explicitly:** per-user (Postman, Katalon), per-request-volume (BlazeMeter), per-seat (Katalon True Automation), and usage-based add-ons (Postman monitoring/AI/performance) produce different costs at the same testing volume.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not list Cypress or Playwright as API testing tools, present Dredd as actively maintained, or fabricate star counts for Tavern or REST Assured.
