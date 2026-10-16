# Awesome-Survey-Feedback-Management

# Top Survey & Feedback Management Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Form Building, Response Collection & Insight Generation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Survey & Feedback Management**. These tools help teams build forms and surveys, distribute them across channels, collect responses, and analyze results — with options ranging from polished commercial platforms with AI-powered insights to fully self-hosted, headless survey infrastructure that keeps sensitive data within your own infrastructure.

**Examples** include Typeform, SurveyMonkey, Jotform, Google Forms, Qualtrics, Formstack, SurveySparrow, Zoho Survey, QuestionPro, and Alchemer (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, headless survey architectures, and transparent data ownership — ideal for teams prioritizing privacy, avoiding per-response pricing, and maintaining full control over survey data.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Typeform](https://www.typeform.com/)**  
  **The design-led survey platform known for conversational, one-question-at-a-time forms that people actually complete.** Trusted by 95% of the Fortune 500 . Free plan available; paid tiers scale by response volume. Features **Creator AI** for form building, **Interaction AI** for adaptive follow-up questions, and **Insights AI** for analyzing open-text responses . Integrates with 300+ apps including HubSpot, Salesforce, Slack, and Google Sheets. **Best for teams prioritizing respondent experience and completion rates** over deep research methodology.

- **[SurveyMonkey](https://www.surveymonkey.com/)**  
  **The world's most popular survey platform** used by 260,000+ organizations . Free Basic plan: unlimited surveys, 10 questions each, 25 responses per survey . Paid plans scale response limits: Standard (1,000/month), Advantage (15,000/year), Premier (40,000/year) . **Global audience panel of 335M+ people in 130+ countries** for targeted research . **Best for teams wanting a trusted, well-known platform with strong benchmarking capabilities**.

- **[Jotform](https://www.jotform.com/)**  
  **Feature-rich form builder with the broadest product suite** — includes form builder, Jotform Apps, Tables, PDF Editor, Sign (e-signatures), Workflows, and Report Builder . **Free Starter plan** with 5 forms, 100 monthly submissions, and 100 MB storage. Paid tiers scale to unlimited forms and high submission volumes. **HIPAA compliance features available on Gold and Enterprise plans** . **Best for organizations needing forms plus adjacent workflow tools** in one platform.

- **[Google Forms](https://forms.google.com/)**  
  **The simplest, most accessible survey tool** — included free with any Google account. Create forms directly in Google Drive or Sheets, with responses stored in Google Sheets for analysis . **Unlimited forms and responses**. Basic question types, simple logic, and real-time charts. **Best for quick internal surveys and feedback collection** where ease of use trumps advanced features.

- **[Qualtrics](https://www.qualtrics.com/)**  
  **The enterprise experience management platform** for sophisticated research programs. Gartner Peer Insights reviewers praise **powerful survey customization and robust analytics/dashboards** for visualizing trends and KPIs . However, reviewers also note the platform can feel **"glitchy and difficult to use for new users"** . **Best for large organizations running complex, ongoing research programs** with dedicated research teams.

- **[Formstack](https://www.formstack.com/)**  
  **The native Salesforce forms solution** — forms are built entirely within Salesforce, with all data collected, processed, and stored directly in Salesforce . This means **no data leaves the Salesforce security model**, leveraging GDPR and HIPAA compliance and compatibility with Salesforce Shield . Trusted by 32,000+ organizations including Kaiser Permanente, Shell, Shopify, and Netflix. **Best for Salesforce-native organizations** that want forms without external data exposure.

- **[SurveySparrow](https://surveysparrow.com/)**  
  **Conversational survey platform** with a chat-like respondent experience designed to improve completion rates . **Mobile-first design** that works like a messaging app. Built-in **Survey Automation** for recurring surveys. **Best for HR teams and customer feedback programs** wanting higher engagement than traditional forms.

- **[Zoho Survey](https://www.zoho.com/survey/)**  
  **Survey tool within the Zoho ecosystem** with 250+ templates . Free plan: 100 responses per survey monthly. Paid plans scale to 3,000–7,000 responses monthly . **26+ language builder UI** and **90+ language survey translation** . Deep integrations with Zoho CRM, Zoho Sheet, Zendesk, Shopify, and Google Sheets. **Best for organizations already using Zoho apps** wanting native integration.

- **[QuestionPro](https://www.questionpro.com/)**  
  **Free survey software designed not to be outgrown** — free Essentials plan with unlimited questions and **up to 200 responses per survey** . **QuestionPro AI** drafts surveys, reads open-ends, and builds dashboards in one click . **MCP support** connects Claude, ChatGPT, or Cursor directly to your QuestionPro account . Compliance with CCPA, GDPR, ISO 27001, and HIPAA . **Best for teams wanting a generous free tier with AI capabilities**.

- **[Alchemer](https://www.alchemer.com/)**  
  **Powerful survey software with 43 question types and advanced logic** . Trusted by 11,000+ companies. **Alchemer AI** creates surveys from prompts, reveals the "why" with dynamic follow-ups, and surfaces insights in plain language . Integrates with 400+ systems including WordPress, UKG, Unanet, Zoho Sign, and Zendesk . **Best for teams needing complex logic and enterprise integrations** without enterprise pricing.

## Open-Source GitHub Projects

- **[Formbricks](https://github.com/formbricks/formbricks)**  
  **The leading open-source survey infrastructure for modern software companies.** AGPL-licensed with **headless survey capabilities** — Formbricks handles survey definitions and response collection via APIs, while you render surveys in your own frontend and forward data to your own analytics pipelines . **Self-hostable with no vendor lock-in.** Features **Management API** for programmatic survey creation, **Client API** for response submission without authentication, and **Webhooks** for real-time response delivery to your data warehouse or CRM . Enterprise license allows forking the surveys package for private customization without AGPL obligations . **Best for product teams embedding surveys into their own applications.**

- **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)**  
  **The most mature open-source survey platform** — free, self-hosted, with a comprehensive feature set . Supports **multi-language surveys**, question groups, advanced branching logic, and ExpressionScript for complex conditions. **Self-hosted installation gives full data sovereignty**. Cloud hosting available for teams preferring managed deployment. **Best for research teams and organizations needing complete control** over survey infrastructure and respondent data.

- **[EUSurvey](https://github.com/EUSurvey/EUSurvey)**  
  **The European Commission's official survey management tool** — fully open source under the EUPL license . Launched in 2013, it powers **public consultations and staff surveys** across EU institutions. Features **23 EU language interfaces**, form translation into 136 ISO 639-1 languages, **dependent questions** for interactivity, scheduled publishing, offline answering, and **enhanced contrast for visually impaired participants** . **Best for government, public sector, and EU-adjacent organizations** needing multilingual, accessible surveys.

- **[SurveyJS](https://github.com/surveyjs/survey-library)**  
  **Client-side form management software that never stores or transmits your data to external services** . Distributed as npm packages for React, Angular, Vue3, and vanilla JavaScript. **MIT-licensed Form Library** renders interactive forms; **Survey Creator** provides drag-and-drop building with JSON output; **Dashboard** visualizes results; **PDF Generator** exports fillable PDFs . **Full data ownership** — you decide where data is stored, encrypted, and accessed. GDPR, HIPAA, and FERPA compliant by architecture . **Best for enterprises requiring complete data sovereignty** and embedding forms natively into applications.

- **[formbricks/formbricks](https://github.com/formbricks/formbricks)** (alternate reference)  
  See Formbricks entry above for headless survey details.

### Additional Strong Open-Source Options

- **Open Source Survey Tool (OSS Survey)** — Lightweight self-hosted survey platform with basic question types and response export.
- **TellForm** — Open-source form builder with branching logic and analytics. Self-hostable.
- **OhMyForm** — Open-source form and survey builder with a clean interface and API access.
- **SurveyJS Creator** — Standalone drag-and-drop form builder producing JSON schemas for any SurveyJS renderer.

**Frameworks for building custom systems**: Combine **Formbricks** for headless survey infrastructure with API-driven definitions and webhooks, **SurveyJS** for embedding MIT-licensed form rendering directly into your application with full data sovereignty, **LimeSurvey** for comprehensive self-hosted survey management with advanced logic, and **EUSurvey** for multilingual accessibility requirements — to build a complete survey and feedback stack tailored to your data governance needs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Survey and feedback tools differ significantly in data residency, AI capabilities, and integration philosophy. **Formstack for Salesforce stores all data within Salesforce** — eliminating external data exposure but requiring Salesforce licensing . **SurveyJS never transmits data to external services** — you own storage entirely . **Typeform's AI features and SurveyMonkey's audience panel are commercial advantages** not replicated in open-source alternatives. **Google Forms is free but limited** in logic and branding compared to paid platforms.
- Self-hosted open-source solutions require proper security hardening, backup strategies, and ongoing maintenance.

---

**Made for product teams, researchers, HR professionals, marketers, and developers building survey and feedback platforms.**  
Let's make survey and feedback management more open, data-sovereign, and respondent-friendly.
