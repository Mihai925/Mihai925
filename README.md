<div align="center">

# Mihai Jiplea

### I build B2B SaaS for e-commerce

**Seattle, WA** &nbsp;·&nbsp; previously Splunk, Google, AWS &amp; Amazon

<a href="https://www.linkedin.com/in/mihaijiplea"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:mihai@jiplea.com"><img src="https://img.shields.io/badge/Email-C14438?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://chatbuster.com"><img src="https://img.shields.io/badge/chatbuster.com-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="chatbuster.com"></a>
<img src="https://img.shields.io/badge/agumail.com-coming_soon-F59E0B?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=111827" alt="agumail.com, coming soon">

</div>

---

For eleven years I worked on other companies' infrastructure. In January 2026 I left to build my own products for online stores.

<br>

## 🤖 My rules for working with AI

I use AI daily, but I use it the right way. I have some simple rules to avoid slop and design that looks "ai-generated" (you know what I mean):

- 🧩 **The model matters.** Claude for code, Nano Banana for assets, DeepSeek for writing. That last one is a pure quality judgement, obviously, and has nothing whatsoever to do with DeepSeek being the one that still doesn't watermark its output. 🤫
- 🎯 **Never let it get creative.** A model is built to reproduce patterns, not to think, so originality is not a thing you can request. Work out the best approach yourself, then hand it over as the pattern to imitate.
- 🛡️ **Guardrail everything.** Every byte a model reads is untrusted input. Assume prompt injection is coming and make sure that when it lands, there is nothing behind it worth reaching.
- 🔍 **Own the architecture.** Read every line before it ships and understand why it is there. The model types faster than I do, but it is not the one accountable for the system.

<br>

## 🟢 ChatBuster · live

**AI chat that answers from your actual store.**

Most storefront chatbots will cheerfully invent a price or a return window. ChatBuster syncs your live catalog, pages and policies, so every answer comes from real store data. It also handles *"where's my order?"* without anyone opening a support ticket.

- 🧠 **Trained on your catalog automatically**, with no uploads, no prompt files, and no API keys to babysit
- 📦 **Real order tracking** for guests and logged-in customers
- ✍️ **One-line corrections** that fix a wrong answer straight from the transcript, no retraining
- 🎯 **Proactive campaigns** on exit intent, dwell time or scroll depth
- 🌍 **Replies in the shopper's language**, automatically
- ⚡ **Live in under two minutes** on any theme

<a href="https://apps.shopify.com/chatbuster-app"><img src="https://img.shields.io/badge/Shopify_App_Store-95BF47?style=flat-square&logo=shopify&logoColor=white" alt="Shopify App Store"></a>
<a href="https://wordpress.org/plugins/chatbuster/"><img src="https://img.shields.io/badge/WordPress.org-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress.org"></a>
<a href="https://chatbuster.com"><img src="https://img.shields.io/badge/chatbuster.com-111827?style=flat-square&logo=googlechrome&logoColor=white" alt="chatbuster.com"></a>

⭐⭐⭐⭐⭐ on the Shopify App Store and WordPress.org.

<br>

## 🟡 AguMail · building now

**Ecommerce email marketing without the enterprise price tag.**

Every incumbent charges you by the size of your list, including the people who already unsubscribed. AguMail bills only for contacts who actually want your email, and sends are unlimited on every paid plan. It runs on SES, where a thousand emails cost about ten cents.

- ♾️ **Unlimited sends** on every paid plan, priced on *active* contacts only
- 🛒 **Ecommerce flows** for abandoned cart, browse abandon, win-back, replenishment and cross-sell
- 🔮 **Predictive segmentation** using RFM, lifetime value and churn risk
- 💌 **Deliverability suite** with MX validation, disposable-domain screening and reputation monitoring
- 📊 **Revenue attribution** down to the flow and the product
- 🔌 **Shopify &amp; WooCommerce** sync out of the box

<img src="https://img.shields.io/badge/agumail.com-coming_soon-F59E0B?style=flat-square&logo=googlechrome&logoColor=white&labelColor=111827" alt="agumail.com, coming soon">

Currently deep in deliverability and import tooling.

<br>

## 📦 medusa-event-bus-sqs · open source

**An SQS event bus for [Medusa](https://medusajs.com).**

Medusa ships with an in-memory event bus, which means events die with the process and cannot be shared between instances. This module puts AWS SQS underneath instead, so you get at-least-once delivery, event grouping, and workers that scale horizontally. Community plugin, MIT licensed, published on npm.

<a href="https://www.npmjs.com/package/medusa-event-bus-sqs"><img src="https://img.shields.io/npm/v/medusa-event-bus-sqs?style=flat-square&logo=npm&logoColor=white&color=CB3837&label=npm" alt="npm"></a>
<a href="https://github.com/Mihai925/medusa-event-bus-sqs"><img src="https://img.shields.io/badge/source-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>

<br>

<details>
<summary><b>💼 Eleven years before I went solo</b> (click to expand)</summary>

<br>

| When | Where | What |
| --- | --- | --- |
| 2025 – 2026 | **Splunk** · Staff Software Engineer | Ingest Protocols &amp; Services |
| 2022 – 2025 | **Splunk** · Senior Software Engineer | Ingest Protocols &amp; Services |
| 2020 – 2022 | **Google** · Software Engineer | Storage @ GCP |
| 2019 – 2020 | **AWS** · SDE II | Lambda control plane |
| 2018 – 2019 | **Amazon** · SDE II, Seattle | Alexa |
| 2015 – 2018 | **Amazon** · SDE, London | Vendor technologies |

🎓 Imperial College London. The work was mostly distributed systems, control planes and data ingest at scale.

</details>

<br>

## 🛠️ What I build with

I'm a polyglot programmer. I pick the language that fits the job, that the platform already speaks, and that has the most support behind it when something breaks at 2am. Over eleven years that has meant Java at Amazon, C++ at Google and Splunk, and TypeScript across everything I ship today.

| | |
| --- | --- |
| **Today** | `TypeScript` · `Node` · `React` · `PHP` |
| **Before** | `Java` at Amazon · `C++` at Google and Splunk |
| **Platform** | `AWS CDK` · `Lambda` · `SES` · `SQS` · `Postgres` · `Prisma` |
| **Commerce** | `Shopify` · `WooCommerce` · `Medusa` · `Stripe` |

<br>

---

<div align="center">

## 💬 Working on B2B SaaS? Let's talk.

Founders, operators, indie hackers, anyone selling software to merchants.
I'm always up for comparing notes on pricing, distribution
and app store review queues.

No pitch needed, just say hi.

**[LinkedIn](https://www.linkedin.com/in/mihaijiplea)** &nbsp;·&nbsp; **[mihai@jiplea.com](mailto:mihai@jiplea.com)**

</div>
