<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rackmoon/.github/main/profile/assets/rackmoon-horizontal-night.svg">
  <img alt="RackMoon" src="https://raw.githubusercontent.com/rackmoon/.github/main/profile/assets/rackmoon-horizontal-day.svg" width="340">
</picture>

**Billing, provisioning and AI agents for hosting and cloud providers.**

From one rack to the moon.

</div>

RackMoon is a self-hosted business system for small and mid-sized hosting and cloud providers. It brings billing, automatic provisioning, a client area, support tickets and a supply network into one place. Sell VPS, dedicated servers, GPUs, containers, game servers, domains or web hosting from the same billing engine. The core will be free, and we plan to open-source it.

> **Status:** early design. We are building in the open, and nothing is ready for production yet. Follow this organization to keep up.

## What we are building

- **One billing engine, seven ways to charge.** Monthly, hourly from a prepaid balance, dynamic usage, per second, per token, per GB or 95th percentile, and yearly or one-time. When a balance runs low, services slow down instead of running up debt.
- **Billing decoupled from provisioning.** Every product type plugs in through one provider contract. Adding a VPS panel, a game panel, a GPU marketplace or a domain registrar never touches billing code.
- **A supply network between merchants.** Resell another provider's products with automatic provisioning. Money moves directly between merchants, and RackMoon never holds funds.
- **AI agents that act safely.** A support agent comes first, then growth, admin and risk agents. Each action is read-only, confirmed by the customer, or approved by the merchant, and every action is logged.
- **Ready to sell worldwide.** A client area in English and Chinese; Stripe, PayPal and USDT, with Alipay and WeChat Pay through licensed channels; coupons and affiliates built in.

## Roadmap

| Phase | Focus |
| --- | --- |
| MVP | Billing core and balances, bilingual client area, payments, tickets, coupons and affiliates, two provider plugins (one VPS panel, one game panel), a basic supply network, a support agent limited to low-risk actions |
| Next | Usage-based billing (dynamic, per GB, per second, per token), growth and admin agents, an MCP server, migration from WHMCS, GPU and on-demand game server providers, EU VAT invoicing, a supply marketplace |
| Later | A risk agent, inference and sandbox APIs, a plugin and theme marketplace |

## Get involved

- Questions and ideas: [open an issue](https://github.com/rackmoon/.github/issues).
- Security reports: follow the [security policy](https://github.com/rackmoon/.github/blob/main/SECURITY.md). Please do not file them as public issues.

## 中文简介

从一个机柜出发，奔向月亮。

RackMoon 是给中小主机商和云服务商用的一站式经营系统，可以自己部署。计费、自动开通、客户中心、工单、上下游货源都在一套系统里，再加上能安全执行操作的 AI agent。VPS、独立服务器、GPU、容器、游戏服、域名、虚拟主机，都用同一套计费引擎来卖。核心系统免费，计划开源。

项目还在设计阶段，正在公开开发，暂时不能用于生产环境。欢迎关注。
