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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Google Ads**
  **Search, display, video, and shopping advertising** on Google's network. **Pricing**: Auction-based; pay per click or impression. **Free tier**: None (ad spend required). **Best for**: businesses wanting access to Google's search intent data—**trade-off**: complexity across campaign types; costs scale with competition.

- **Meta Ads Manager**
  **Facebook and Instagram advertising** with detailed targeting and creative formats. **Pricing**: Auction-based; pay per impression or action. **Free tier**: None. **Best for**: social advertising with granular audience targeting—**trade-off**: iOS privacy changes reduced attribution accuracy.

- **HubSpot Ad Management**
  **Ad campaign management** within HubSpot CRM. **Pricing**: Included with Marketing Hub Professional ($890/month) and Enterprise. **Free tier**: Limited. **Best for**: HubSpot users wanting ad ROI tied to CRM contacts—**trade-off**: limited to Google, LinkedIn, and Facebook; no programmatic.

- **Marin Software**
  **Cross-channel advertising management** for search, social, and retail media. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises managing large cross-channel budgets—**trade-off**: enterprise pricing; implementation complexity.

- **Skai**
  **Omnichannel advertising platform** for retail media and paid search. **Pricing**: Quote-only. **Free tier**: None. **Best for**: retailers and brands managing retail media networks—**trade-off**: sales-led; enterprise focus.

- **Smartly.io**
  **Creative automation and social advertising** platform. **Pricing**: Quote-only. **Free tier**: None. **Best for**: brands producing high volumes of social creative—**trade-off**: creative-focused; not full cross-channel.

- **RollWorks**
  **Account-based advertising** for B2B. **Pricing**: Quote-only. **Free tier**: None. **Best for**: B2B teams targeting specific accounts—**trade-off**: ABM-focused; limited to B2B use cases.

- **AdRoll**
  **Retargeting and display advertising** for SMBs. **Pricing**: Usage-based; quote for managed service. **Free tier**: Trial available. **Best for**: SMBs wanting simple retargeting—**trade-off**: limited to display and social retargeting.

- **WordStream**
  **PPC management software** with Google Ads optimization. **Pricing**: Quote-only. **Free tier**: Free Google Ads Grader tool. **Best for**: SMBs wanting guided PPC management—**trade-off**: Google-focused; limited multi-platform.

- **Perpetua**
  **Amazon advertising optimization** platform. **Pricing**: Quote-only. **Free tier**: None. **Best for**: Amazon sellers and vendors—**trade-off**: Amazon-only; not for general digital advertising.

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
