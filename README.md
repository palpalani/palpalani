# Palaniappan P

Director of Technology at [TargetBay](https://targetbay.com/). Chennai, India.

I have been building web and SaaS systems since 2002. I set architecture and engineering direction for TargetBay’s product suite: multi-tenant eCommerce marketing across email and SMS, reviews, loyalty, and deliverability. The same production work is behind the Laravel packages I maintain, and the n8n and LLM workflows I use to automate engineering and operations.

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
