# Awesome-API-Changelog-Version-History

# Awesome-API-Changelog-Version-History

**Top API Changelog Version History (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Public Roadmaps, In-App Widgets, Release Notes Automation & Self-Hosted Feedback Boards*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Changelog & Version History**. These tools enable product teams to announce releases, publish public changelogs, collect feedback on upcoming features, and keep API consumers informed about breaking changes—from fully managed platforms with in-app widgets and segmentation to open-source boards that give teams complete control over their release communications and data.



**Examples** include Headway, Noticeable, Beamer, AnnounceKit, Canny, LaunchNotes, Frill, Productlane, and ReleaseNotes.io (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted changelogs, feedback boards, and open release infrastructure. **Critical note**: True open-source changelog platforms are sparse—**Refyyn** is the most complete open-source alternative, combining a public feedback board, roadmap, and changelog in one self-hosted Laravel application . **github-changelog-generator** automates changelog generation from Git metadata but does not provide a hosted public page . No open-source project matches Beamer's in-app widget segmentation or Canny's AI-powered feedback deduplication, but for teams wanting a self-hosted public changelog, Refyyn fills the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Headway**

  **Minimalist changelog and "what's new" widget**. **Pricing**: **Free plan** with basic feature set; **Pro plan $29/month** (was free during beta, pricing now finalized) . **Free tier**: Yes, basic features. **Best for**: small teams wanting a clean, no-frills changelog without per-MAU metering—**trade-off**: fewer segmentation and targeting features than Beamer or Canny; no official MCP server listed .



- **Noticeable**

  **Changelog and newsfeed with per-publication email**. **Pricing**: **Free** (watermark, 1 project); **Starter $29/month** (~$24 annual); **Growth $79/month**; **Business $159/month**; **Enterprise $399/month** . **Critical cost**: **Email delivery is charged per dispatch** on top of the plan—a cost that grows with every publication sent to subscribers . **Free tier**: Yes, with watermark. **Best for**: individuals and small teams wanting a changelog widget plus email at a low entry point—**trade-off**: **no collaborators on Starter**; GraphQL API and scheduling require Growth ($79/month) .



- **Beamer**

  **In-app "what's new" widget with segmentation**. **Pricing**: **Free** (1,000 MAU); **Starter $59/month** ($49 annual, 5,000 MAU); **Pro $119/month** ($99 annual, 10,000 MAU); **Scale $299/month** ($249 annual, 50,000 MAU). Additional MAUs in **5,000 blocks at $50/month** . **Free tier**: Yes, 1,000 MAU. **Best for**: SaaS companies wanting in-app announcements with segmentation and a dedicated inbox—**trade-off**: **feedback and NPS are paid add-ons on every tier** ($99 each on Pro) .



- **AnnounceKit**

  **Modular changelog and announcement widgets**. **Pricing**: **Changelog $59/month** ($49 annual, 10,000 MAU included, then $25 per 5,000); **Email add-on $39/month** (annual, no per-subscriber fee); **Feature Requests & Roadmap $49/month**; **Product Tours $69/month**. 15-day free trial, every add-on included . **Free tier**: Trial only. **Best for**: teams wanting a changelog widget with a separate email add-on priced predictably—**trade-off**: **modular pricing means costs stack**; the $59 changelog alone does not include email delivery .



- **Canny**

  **Feedback management with changelog**. **Pricing**: **Free plan** now includes **25 tracked users**, unlimited feedback integrations, unlimited posts and boards, and **unlimited Autopilot** (AI deduplication) . **Paid plans from $19/month** with 100 tracked users; **Pro from $79/month** adds email notifications for changelog publishing . **Free tier**: Yes, 25 tracked users. **Best for**: teams wanting feedback collection and changelog in one platform with a genuine free tier—**trade-off**: **email notifications for changelog require Pro**; changelog itself is free with no restrictions .



- **LaunchNotes**

  **Release notes and product communication** platform. **Pricing**: **From $249/month annual** (seat-based, 2 seats) per AnnounceKit comparison . SourceForge lists **starting at $29/month** (scope unclear—likely a different tier or outdated) . **Free tier**: Not available per Software Advice . **Best for**: enterprises wanting structured release communication workflows—**trade-off**: pricing data conflicts across sources; verify directly.



- **ReleaseNotes.io**

  **Release notes and changelog platform**. **Pricing**: Not detailed in available search results. **Free tier**: Not specified. **Best for**: teams wanting a focused release notes tool—**trade-off**: limited public pricing data.



- **Frill**

  **Feedback and roadmap platform**. **Pricing**: Not detailed in available search results. **Free tier**: Not specified. **Best for**: teams wanting feedback and roadmap in one tool.



- **Productlane**

  **Customer feedback and changelog** platform. **Pricing**: Not detailed in available search results. **Free tier**: Not specified. **Best for**: product teams wanting feedback-to-changelog workflows.



## Open-Source GitHub Projects



- **Refyyn**

  **Free, open-source, self-hosted customer feedback tool with kanban roadmap and changelogs** (MIT) — **the most complete open-source changelog and feedback platform** found in this research . **Features**: **Admin dashboard**—manage feedback, change statuses, organize into boards; **Public feedback board**—users submit feedback, upvote, and comment; **Public roadmap**—share what's planned, in progress, and completed; **Changelog**—publish updates and release notes . **Tech stack**: Laravel 12, Vue 3, Inertia.js, Tailwind CSS, SQLite/MySQL/PostgreSQL . **Deploy**: Self-hosted (PHP 8.2+, Composer, Node.js 22+; `php artisan migrate` then `php artisan serve`) . **Trade-off**: **Feedback board focus**—changelog is one module, not a standalone changelog tool with in-app widgets or email delivery; newer project with limited community validation. **Best for**: teams wanting a self-hosted feedback board with a public changelog—especially those wanting to own their product communication data without per-MAU pricing .



- **github-changelog-generator**

  **Automatically generate changelog from GitHub metadata** (MIT) — **the most starred open-source changelog automation tool**, with **7,442 stars** . **Features**: **Generates changelog from tags, issues, labels, and pull requests**; **Ruby-based** CLI; configurable output format; integrates into release workflows . **Tech stack**: Ruby. **Deploy**: CLI (`gem install github_changelog_generator`). **Trade-off**: **Generation only**—it produces a CHANGELOG.md file; no hosted public page, no in-app widget, no feedback collection. **Best for**: developers wanting to automate CHANGELOG.md generation from GitHub activity—not a customer-facing changelog platform .



### Additional Strong Open-Source Options



- **next-release** — Release note management platform (open source, JavaScript). Automates release notes in 3 clicks . **Note**: **Inactive**—last pushed over 2 years ago; 18 stars. **Best for**: reference only—do not adopt for new deployments .

- **No mature open-source equivalent to Beamer's in-app widget or Canny's AI feedback deduplication exists.** Refyyn provides the closest approximation for a self-hosted feedback board with changelog, but lacks in-app widget segmentation and email delivery.



**Frameworks for building custom systems**: **Refyyn** provides the self-hosted feedback board and changelog foundation; **github-changelog-generator** automates CHANGELOG.md generation. **Neither matches Beamer's in-app widget or AnnounceKit's email delivery.** For customer-facing changelog communication at scale, commercial platforms are required.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Changelog platforms handling subscriber data and product information must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "changelog widget" vs. "feedback board" vs. "release notes automation" distinction is critical.** **Headway, Noticeable, Beamer, and AnnounceKit** are **changelog widgets**—they display release announcements in-app or on a public page . **Canny** is a **feedback board with changelog**—it prioritizes feedback collection and voting . **LaunchNotes** is **release notes communication**—it focuses on structured announcements . **Refyyn** is an **open-source feedback board with changelog**—it combines feedback, roadmap, and changelog in one self-hosted tool . **github-changelog-generator** is **release notes automation**—it generates a file, not a hosted page . **Choose based on whether you need customer-facing announcements, feedback collection, release communication workflows, or file generation.**

- **Noticeable's email delivery is charged per dispatch on top of the plan**—a cost that grows with every publication sent to subscribers . **Model your email volume before choosing a tier**; Growth ($79/month) is required for GraphQL API, scheduling, and collaborators beyond zero .

- **Beamer's feedback and NPS are paid add-ons on every tier**—$99 each on Pro . **A changelog + feedback + NPS on Pro costs $297/month annual** . **Do not assume the base plan includes these features** .

- **AnnounceKit's changelog ($59/month) does not include email delivery**—the Email add-on is **$39/month** separately . **The modular pricing means the full package costs more than the headline number** .

- **Canny's free tier now includes 25 tracked users and unlimited Autopilot**—the most generous free tier in the category . **Email notifications for changelog publishing require Pro ($79/month)** .

- **Headway's Pro plan is $29/month**—the lowest paid entry point in the category . **The trade-off**: fewer features than Beamer or Canny; no official MCP server .

- **Refyyn is the only functional open-source option**—MIT licensed, self-hosted, with feedback board, roadmap, and changelog . **The trade-off**: feedback board focus; no in-app widget or email delivery. **For teams wanting to own their product communication data, it is the starting point.**

- **LaunchNotes pricing data conflicts**—AnnounceKit comparison lists $249/month annual, SourceForge lists $29/month starting . **Verify directly with LaunchNotes before evaluating** .

- Self-hosted open-source solutions require proper infrastructure (PHP 8.2+, Composer, Node.js 22+ for Refyyn) and ongoing maintenance. **Changelog data includes product roadmap and release information**—ensure your deployment meets your organization's security requirements before publishing.



---



**Made for product managers, developer relations teams, and organizations building transparent changelog solutions.**

Let's make API Changelog & Version History more open, data-driven, and release-friendly.
