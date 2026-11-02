# Awesome-Digital-Advertising-Management

# Awesome-Digital-Advertising-Management

**Top Digital Advertising Management (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Campaign Management, Ad Serving, AI-Powered Optimization & Self-Hosted Ad Infrastructure*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Advertising Management**. These tools enable marketers and developers to plan, launch, and optimize ad campaigns across search, social, and programmatic channels—from fully managed platforms with AI bidding and cross-channel analytics to open-source ad servers and agent frameworks that give teams control over their ad infrastructure.



**Examples** include Google Ads, Meta Ads Manager, HubSpot Ad Management, Marin Software, Skai, Smartly.io, RollWorks, AdRoll, WordStream, and Perpetua (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted ad serving, campaign management, and open advertising automation. **Critical note**: The open-source landscape is segmented by function—**Revive Adserver** is the most mature self-hosted ad server for publishers , **openadserver** provides ML-powered CTR prediction with a modern Python stack , and **advertising-hub** offers MCP servers and AI agents for managing Google Ads, Meta, and 12+ platforms . No open-source project matches Google Ads' auction mechanics or Skai's cross-channel optimization, but for specific layers of ad management, the options are functional.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global digital advertising market is estimated at approximately **$600B–$740B** (projected to surpass $1T+ by 2030), characterized by a dual market structure: **highly concentrated** at the infrastructure layer where a "walled-garden" oligopoly (Google, Meta, and Amazon) commands the vast majority of digital ad revenues, yet **moderately-to-highly fragmented** at the campaign execution, multi-channel attribution, and tooling layer where specialized SaaS platforms and point solutions compete to optimize cross-channel media spend.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Pricing Tier | Free Tier / Free Trial Limits | Key Focus & Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **Google Ads** | ~$2.1T Market Cap / $260B+ Ad Revenue (Alphabet) | $0 platform fee; pay-per-click/impression auction ($5/day recommended starter spend) | Free to create account; eligible new accounts get a $500 matched ad credit (must spend $500 within 60 days, credit expires in 60 days) | Search, display, video (YouTube), and shopping ads powered by Google's global search intent and algorithmic bidding. |
| **Meta Ads Manager** | ~$1.5T Market Cap / $160B+ Ad Revenue (Meta Platforms) | $0 platform fee; pay-per-impression auction ($1–$5/day minimum ad spend depending on objective) | Free access to platform and audience tools; no free ad spend tier or public trial (periodic targeted $5–$50 partner credits only) | Facebook, Instagram, and WhatsApp ad campaigns with granular demographic and algorithmic audience targeting. |
| **HubSpot Ad Management** | ~$32B Market Cap / $2.6B Revenue (HubSpot) | Free tier available; Starter at $15/seat/month; advanced ad management in Marketing Hub Pro at $890/month | Free forever plan includes ad management connecting up to 2 ad accounts (Google, Facebook, LinkedIn) with basic tracking | Native ad management integrated directly with HubSpot CRM to tie campaign ROI directly to lifecycle contacts and deals. |
| **Perpetua** | $835M Acquisition (Division of Omnicom / Flywheel) | $695/month (Essentials plan covering up to $10,000 monthly ad spend) | No self-serve free trial; guided 1-on-1 personalized platform demo available | AI-driven Amazon, Walmart, and Target marketplace advertising optimization, programmatic DSP, and bid automation. |
| **NextRoll (AdRoll)** | ~$580M Peak Valuation / ~$100M+ Revenue | $36/month (Starter tier for single-channel display/social retargeting + ad spend) | 30-day free trial; free tier available at $0/month platform fee for basic tracking pixel setup & up to 2,500 email contacts (media spend billed separately) | Cross-channel retargeting, display, and social advertising automation tailored for direct-to-consumer and SMB brands. |
| **NextRoll (RollWorks)** | ~$580M Peak Valuation / ~$100M+ Revenue | $975/month (~$11,700/year annual commitment for ABM Starter + media spend) | No free trial; free tier includes basic self-serve retargeting pixel setup; advanced ABM & intent features require custom demo/paid plan | B2B account-based marketing (ABM) and account-based advertising platform connecting target accounts with CRM data. |
| **Skai** | ~$450M Valuation / ~$100M+ Revenue | $9,500/month ($114,000/year billed annually on Standard tier for up to $4M annual ad spend) | No free trial; offers custom platform walk-through and 90-day review checkpoint on annual contracts | Enterprise omnichannel advertising platform connecting retail media networks, search, and paid social with predictive analytics. |
| **Smartly.io** | €300M (~$330M) Valuation / €70M+ Revenue | ~$4,000–$5,000/month minimum platform fee (or 3%–5% of managed ad spend, whichever is greater) | No free trial or self-serve tier; demo-based onboarding with strict annual enterprise commitments | Enterprise dynamic creative automation and performance social advertising across Meta, TikTok, Pinterest, and Google. |
| **WordStream** | Subsidiary of Gannett / LocaliQ (~$600M Market Cap) | ~$244/month (or custom bundles starting at ~$500/month with LocaliQ digital marketing services) | No software free trial; provides unlimited free forever standalone tools (Google Ads Performance Grader and Free Keyword Tool) | Guided PPC management, automated account audits, and cross-channel campaign suggestions for SMBs and local businesses. |
| **Marin Software** | ~$2.8M Market Cap / ~$17.5M Revenue (MRIN) | $500/month (Connect tier with month-to-month terms; Ascend at $1,000/month; One at $2,000/month) | 30-day free trial / sandbox account available for testing publisher and data feed integrations | Cross-channel enterprise campaign management, budget allocation, and bidding optimization for search, social, and retail media. |



## Open-Source GitHub Projects



- **Revive Adserver**

  **Free open source ad serving system** (GPL v2) — **the world's most popular open-source ad server**, used by publishers, ad networks, and advertisers to serve ads on websites, apps, and video players . **Features**: **Campaign management** for multiple advertisers and ad networks from one interface; **delivery rules** including frequency capping, URL targeting, and geo-targeting; **detailed statistics** on impressions, clicks, conversions, revenue, eCPM, and basket value; **self-hosted** with no licensing fees . **Tech stack**: PHP, MySQL. **Deploy**: Self-hosted (web server with PHP/MySQL). **Trade-off**: **Ad serving, not campaign creation**—it serves ads you've already designed; no AI optimization or cross-platform bidding. **Best for**: publishers and ad networks wanting a proven, free ad server with granular delivery controls—the de facto open-source standard for self-hosted ad serving.



- **openadserver**

  **Open Source Ad Serving Platform with ML-Powered CTR Prediction** (open source) — **the most technically advanced open-source ad server**, positioned as a self-hosted alternative to Google Ad Manager . **Features**: **Retrieve → Filter → Predict → Rank → Return** pipeline; **ML-powered CTR prediction** using DeepFM or logistic regression models; **campaign, creative, and advertiser CRUD** APIs; **event tracking** for impressions, clicks, and conversions; **Prometheus metrics** and Grafana dashboards; **Docker Compose** deployment for PostgreSQL, Redis, and ad server . **Tech stack**: Python (FastAPI), PyTorch, PostgreSQL, Redis. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Ad serving infrastructure**—not a campaign management UI for marketers; requires ML model training for CTR prediction. **Best for**: ad tech developers and publishers wanting a modern, ML-capable ad server foundation—especially those building custom ad platforms.



- **advertising-hub**

  **Open-source one-stop shop for advertising platform APIs, MCP servers, and AI agents** (open source) — **the most comprehensive open-source advertising automation framework**, covering **14 platforms** (Google Ads, Meta, Microsoft, Amazon, LinkedIn, Pinterest, Reddit, Spotify, The Trade Desk, Criteo, and more) . **Features**: **25+ AI agents** for paid media divisions—PPC Campaign Strategist, Search Query Analyst, Paid Media Auditor, Creative Strategist, Programmatic Buyer, and platform specialists (Amazon Ads, LinkedIn B2B, Pinterest, Reddit, Spotify, TTD, Demandbase, Criteo) . **MCP servers** giving AI tools (Claude, Cursor, Gemini) direct access to advertising platform APIs; **Google Ads MCP is Live**; **core package** for unified OAuth, normalized models, rate limiting, and error handling . **Tech stack**: TypeScript, Python. **Deploy**: Self-hosted MCP servers; agents run in Claude/Cursor. **Trade-off**: **Agent framework, not a platform**—requires API access to each ad platform; many MCP servers are spec-ready, not live. **Best for**: developers and agencies wanting to automate ad management via AI agents—especially those already using Claude or Cursor for workflows.



- **mureo**

  **AI agent framework for autonomous ad operations** (Apache 2.0) — **the most production-oriented open-source ad automation framework** from a Japanese ad tech company (Logly) . **Features**: **Business strategy-driven operations**—personas, USPs, brand voice, KPIs, and operating modes guide AI decisions; **cross-platform workflow** across Google Ads, Meta Ads, Google Search Console, and GA4 (GA4 via external MCP server) . **Veteran operator judgment encoded**—diagnosing delivery issues, pre-submission checks, search term organization, budget efficiency, device performance analysis; **accumulated operational knowledge**—learns industry-specific patterns and reflects them in future sessions . **Security design**—credential isolation, malicious query blocking, statistical baseline anomaly detection, full write operation logging, one-command rollback, pre-submission policy checks . **Tech stack**: Per repository. **Deploy**: Self-hosted (Claude Code, Cursor, Codex CLI, Gemini CLI). **Trade-off**: **Japanese-language documentation**—English resources limited; newer project with limited Western validation. **Best for**: teams wanting autonomous ad operations with encoded operator judgment—especially those using AI coding agents for workflows.



### Additional Strong Open-Source Options



- **AdVantage (Campaign-Manager)** — Multi-platform campaign management SaaS (MIT). Google Ads, Meta, LinkedIn integration; React Native dashboard for web/iOS/Android; OAuth login; real-time analytics . **Note**: Portfolio/learning project—not production-hardened; requires each platform's API approval. **Best for**: developers wanting a reference for multi-platform campaign dashboards.

- **OpenAdKit** — Browser-only AI marketing and ad generation tool (MIT). 18 AI generators, 11 optimizers, 9 BYOK providers (Claude, GPT, Gemini, Groq, DeepSeek); no backend, no subscription . **Note**: **Ad copy generation, not campaign management**—no API connections or ad serving. **Best for**: marketers wanting AI-generated ad copy without SaaS subscriptions.

- **Simple KUMA** — Self-hosted affiliate and media-buyer tracker (AGPL-3.0). Click/cost/conversion tracking; Meta and Google Ads cost sync; postbacks and pixels . **Note**: **Affiliate tracking, not ad management**—for performance marketers tracking campaigns, not creating them. **Best for**: affiliate marketers wanting self-hosted tracking.



**Frameworks for building custom systems**: Combine **Revive Adserver** for ad serving with **openadserver** for ML-powered CTR prediction and **advertising-hub** for AI agent automation across platforms—creating a layered open-source ad stack. **None of these match Google Ads' auction mechanics or Skai's cross-channel optimization**, but for specific layers, the options are functional.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Digital advertising platforms handling campaign data and user targeting must comply with data protection regulations (GDPR, CCPA, etc.), platform advertising policies, and consent requirements.

- **The "ad server" vs. "campaign management" vs. "AI agent framework" vs. "ad copy generation" distinction is critical.** **Revive Adserver** and **openadserver** are **ad servers**—they serve ads and track impressions/clicks . **Google Ads, Meta Ads Manager, Marin, Skai, and HubSpot** are **campaign management platforms**—they create and optimize campaigns on ad networks. **advertising-hub** and **mureo** are **AI agent frameworks**—they automate ad operations via agents . **OpenAdKit** is **ad copy generation**—it creates creative, not manages campaigns . **Choose based on which layer of ad operations you need to own.**

- **Revive Adserver is the most mature open-source ad server**—used by publishers and networks since 2013, with granular delivery rules and detailed statistics . **The trade-off**: it serves ads you've already designed; no campaign creation or AI optimization.

- **openadserver is the most technically advanced open-source ad server** with ML-powered CTR prediction and a modern Python stack . **The trade-off**: requires ML model training; not a marketer-facing campaign UI.

- **advertising-hub is the most comprehensive open-source ad automation framework**—25+ AI agents across 14 platforms, with Google Ads MCP live . **The trade-off**: many MCP servers are spec-ready, not live; requires API access to each platform.

- **mureo is the most production-oriented open-source ad operations framework** from a real ad tech company, with encoded operator judgment and multi-layer security . **The trade-off**: Japanese documentation; newer to Western audiences.

- **Simple KUMA is for affiliate tracking, not ad management.** It tracks clicks, costs, and conversions for performance marketers—it does not create or serve ads . **Do not confuse it with an ad management platform.**

- Self-hosted open-source solutions require proper infrastructure (PHP/MySQL for Revive, Python/Docker for openadserver), security hardening, and ongoing maintenance. **Ad platforms handle campaign budgets and user targeting data**—ensure your deployment meets your organization's security and compliance requirements before connecting production ad accounts.



---



**Made for marketers, ad ops teams, and organizations building transparent digital advertising solutions.**

Let's make Digital Advertising Management more open, data-driven, and campaign-efficient.
