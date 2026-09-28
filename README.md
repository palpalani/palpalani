# Palaniappan P

Director of Technology at [TargetBay](https://targetbay.com/). Chennai, India.

I have been building web and SaaS systems since 2002. I set architecture and engineering direction for TargetBay’s product suite: multi-tenant eCommerce marketing across email and SMS, reviews, loyalty, and deliverability. Recent work is TarpsNow AI and [FactualMinds AI Agents](https://factualminds.com/ai-agents), alongside the Laravel packages and n8n workflows from those same production systems.

## Platforms

- **[BayEngage](https://app.bayengage.com/)** — Email and SMS marketing automation for eCommerce.
- **[BayRewards](https://bayrewards.io/)** — Loyalty and referral programs.
- **[BayReviews](https://app.targetbay.com/)** — Customer reviews and reputation management.
- **[InboxEagle](https://inboxeagle.com/)** — Email template research with deliverability signals: subject lines, inbox placement, and authentication.
- **[TargetBay](https://targetbay.com/)** — The integrated suite those products belong to.

## How the systems are built

- Multi-tenant SaaS shared across the product lines above.
- Queue-driven transactional messaging on AWS, using SQS and Lambda.
- One architecture spanning email, reviews, rewards, and deliverability.
- AWS cost control across the portfolio: EC2, S3, RDS, Lambda, and SQS.
- Mentoring engineering teams on AI-assisted development and workflow automation.

## Recent work

- **TarpsNow AI** — Internal sales analyst, release v1.0.0 (25 September 2026). A Strands supervisor on Amazon Bedrock AgentCore calls an Odoo analyst and a document analyst. Employees ask in plain language and see the work: SQL, row counts, the Postgres role, data age, and document sources. Odoo lands in Postgres and dbt builds the marts. Documents come from a Bedrock Knowledge Base over Google Drive, plus the mailboxes that person may read. Every query runs as a Postgres role scoped to the asker’s department.
- **[FactualMinds AI Agents](https://factualminds.com/ai-agents)** — The public practice for finding, building, and running eCommerce agents on AWS: support, sales, operations, inventory, and knowledge. Anything that moves money stops for a human approval.

## Open source

Laravel tools maintained from production problems:

- **[laravel-sqs-queue-json-reader](https://github.com/palpalani/laravel-sqs-queue-json-reader)** — SQS queue driver that accepts plain JSON payloads.
- **[laravel-spamassassin-score](https://github.com/palpalani/laravel-spamassassin-score)** — SpamAssassin scoring for message content.
- **[laravel-dns-deny-list-check](https://github.com/palpalani/laravel-dns-deny-list-check)** — DNS deny-list checks for email validation.
- **[laravel-login-notifications](https://github.com/palpalani/laravel-login-notifications)** — Login alerts for account security.
- **[bayrewards-laravel](https://github.com/palpalani/bayrewards-laravel)** — Laravel SDK for BayRewards.
- **[baylinks-laravel](https://github.com/palpalani/baylinks-laravel)** — Laravel SDK for BayLinks.

## Stack

**Application:** PHP, Laravel, Node.js, React, Next.js, Livewire

**Cloud:** AWS (EC2, S3, RDS, Lambda, SQS), Docker, Kubernetes, Terraform

**Data:** MySQL, PostgreSQL, Redis

**Automation:** n8n, LLM workflow automation

**Commerce:** Shopify, WooCommerce, and related store platforms

## Contact

**LinkedIn:** [linkedin.com/in/palpalani](https://www.linkedin.com/in/palpalani/)
**Email:** palani.p@gmail.com
**X:** [@southdreamz](https://twitter.com/southdreamz)
