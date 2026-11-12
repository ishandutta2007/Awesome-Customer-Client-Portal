# Awesome-Customer-Client-Portal

## Top Customer & Client Portal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Client Workspaces, Secure File Sharing & White-Label Self-Service*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer & Client Portals**. These tools give clients a branded, secure workspace to access documents, track project progress, communicate with service teams, and manage their account—replacing scattered email threads and shared drives with a single self-service destination.

**Examples** include SuiteDash, Copilot, Clinked, Onehub, ClientPoint, MyDocSafe, Nimbus Platform, Softr, and open-source alternatives like FileRise, FlowEngine, and ProjectSend (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted client portals, open-source file-sharing workspaces, and community-driven client management—ideal for agencies, consultancies, and service firms seeking data sovereignty and flat-rate pricing over per-client or per-member SaaS subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[SuiteDash](https://suitedash.com/)** | All-in-one client portal with CRM, projects, invoicing, and deep white-labeling. Flat pricing with **unlimited users** on every plan. Positioned as the better consolidation choice versus Copilot, which offers a more polished client experience but lighter operations . | Start: **$19/month** (unlimited users, 100 GB storage); Thrive: $49/month; Pinnacle: $99/month [citation:3][citation:9] | **14-day free trial** of Pinnacle plan, no credit card required [citation:3] |
| **[Copilot](https://copilot.com/)** | Polished client portal focused on client experience. More beautiful and focused than SuiteDash, but lighter on operations (no invoicing/CRM depth). Per-client pricing grows with your client base . | From **$39/month** (annual) [citation:1] | Free trial available |
| **[Clinked](https://www.clinked.com/)** | Document-centric client portal with bank-grade security, granular permissions, audit trails, and compliance features. Per-member pricing with tiers for Standard, Premium, and Enterprise. **SOC 2 Type II** certified; custom domain and white-label mobile app on higher tiers . | Standard: **$239/month** (100 members, 1 TB); Premium: $479/month (250 members, 3 TB); Enterprise: contact sales [citation:4][citation:10] | Free trial available |
| **[Onehub](https://www.onehub.com/)** | Secure file sharing with client branding. "A better Dropbox for clients" with proper permissions and client-side previews without downloads. Less of an all-in-one (no native invoicing or CRM depth) . | Standard: **$45/month** (3 paid users, 200 total users, 50 workspaces, 1 TB); Advanced: $125/month (5 paid users, 1,000 total users, unlimited storage) [citation:5] | **14-day free trial** [citation:5] |
| **[ClientPoint](https://www.clientpoint.com/)** | Client portal and document automation platform focused on proposals, contracts, and client engagement. Often used by sales and service teams for deal rooms and onboarding. | Quote-only | Demo via sales |
| **[MyDocSafe](https://mydocsafe.com/)** | Secure document portal with e-signature, client onboarding, and compliance workflows. Positioned for regulated industries requiring audit trails and data protection. | Quote-only | Demo via sales |
| **[Nimbus Platform](https://nimbusplatform.com/)** | Client portal and project workspace with file sharing, messaging, and task tracking. Positioned for agencies and professional services firms. | Quote-only | Free trial available |
| **[Softr](https://www.softr.io/)** | No-code platform for building client portals on top of Airtable, Google Sheets, or Softr Databases. Enables fully custom portals without engineering. AI features available on higher tiers. Usage-metered pricing model . | Free tier available; paid plans from ~$24/month [citation:13] | **Free plan** available with limited features |
| **[Portal](https://www.portal.com/)** | Client portal (limited public information available in search results; positioned as a client workspace and collaboration tool). | Contact vendor | Contact vendor |
| **[Zoho Client Portal](https://www.zoho.com/)** | Client portal capabilities within the Zoho ecosystem (limited public pricing information available; primarily for Zoho CRM/Desk users). | Included with Zoho subscriptions | Contact Zoho for current availability |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FileRise](https://github.com/error311/FileRise)** | [![Stars](https://img.shields.io/github/stars/error311/FileRise?style=social&color=white)](https://github.com/error311/FileRise/stargazers) | **The most purpose-built open-source client portal with intake forms.** PHP-based web file manager for freelancers, agencies, and small businesses managing sensitive data on their own infrastructure (GDPR-compliant). **Pro version adds Client Portals**: each client gets a dedicated URL (`/portal/<slug>`) with per-portal upload/download permissions, expiration dates, branding (title, instructions, accent color), and optional **Intake Forms** capturing name, email, reference number, and notes before upload. All submissions logged with timestamp, IP, and form values. Docker and Unraid deployment available . |
| **[FlowEngine](https://github.com/flowengine-cloud/flowengine)** | [![Stars](https://img.shields.io/github/stars/flowengine-cloud/flowengine?style=social&color=white)](https://github.com/flowengine-cloud/flowengine/stargazers) | **White-label client portal for automation agencies** (mainly n8n users). Self-hosted, open-source. Manage instances, invite clients, control what they see, and bill them via Stripe. Clients get their own login and see only assigned resources. Includes team member invites, OAuth configuration (Google, GitHub, Microsoft), SMTP for invitations, and Docker Compose deployment with automatic HTTPS via Traefik . |
| **[ProjectSend](https://github.com/projectsend/projectsend)** | [![Stars](https://img.shields.io/github/stars/projectsend/projectsend?style=social&color=white)](https://github.com/projectsend/projectsend/stargazers) | **Mature open-source file-sharing portal for clients** (GPLv2). Share files with clients from your own server. Self-hosted or use ProjectSend Cloud (official hosted version). Long-standing project (updated October 2026) with a dedicated GitHub topic listing under "client-portal" . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[PNLCS](https://github.com/Panelica/pnlcs)** | [![Stars](https://img.shields.io/github/stars/Panelica/pnlcs?style=social&color=white)](https://github.com/Panelica/pnlcs/stargazers) | Open-source WHMCS alternative (Laravel 13, MIT) for hosting billing with **full client portal** including hosting management (files, mail, databases, FTP, subdomains, DNS, cron, backups). Stripe, PayPal, and Authorize.Net gateways. 30 languages, 16 themes. Docker one-command deploy . |
| **[client-portal (Twenty CRM powered)](https://github.com/topics/client-portal)** | — | Self-hosted client portal built on Twenty CRM (TypeScript). Listed on GitHub's `client-portal` topic with a recent October 2026 update. Exact repository URL not confirmed in search results—search GitHub topics for "client-portal" to locate it . |
| **[agency-client-portal](https://github.com/topics/client-portal)** | — | Self-hosted client portal for agencies and freelancers. Manage projects, share files, and give clients a branded portal to track progress. TypeScript-based, listed on GitHub's `client-portal` topic with recent activity . |

**Frameworks for building custom systems**: Combine **FileRise** for branded client upload/download portals with intake forms, **FlowEngine** for white-label agency portals with Stripe billing, and **ProjectSend** for simple file-sharing workspaces—all deployable via Docker without per-client or per-member SaaS fees. For agencies needing a full operations stack, **PNLCS** provides client portal plus hosting management in a single self-hosted package.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Client portals handle sensitive documents, credentials, and sometimes financial data; enforce role-based access, audit logging, and compliance with applicable data protection regulations (GDPR, SOC 2 where relevant).
- **Pricing models vary dramatically and are not directly comparable.** SuiteDash uses **flat pricing with unlimited users** ($19–$99/month) [citation:3][citation:9], while Clinked charges **per member** ($239/month for 100 members) [citation:4] and Copilot scales with client count . Clinked and Moxo offer the strongest compliance features (SOC 2 Type II, audit trails) for regulated data . Open-source alternatives like **FileRise** and **FlowEngine** provide genuine client portal capabilities but require self-hosting effort and lack the polish of commercial platforms. Always model total cost against your projected client count before committing.

---

**Made for agency owners, service operations teams, consultants, and developers building client-facing infrastructure.**  
Let's make customer and client portals more open, branded, and self-service.
