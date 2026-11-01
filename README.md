# Nícollas Frazão

**Senior Backend Software Engineer** · Campinas, Brazil

Backend engineer with 10+ years building production APIs and systems — currently Node.js/TypeScript on AWS, previously PHP/Laravel. Former backend Tech Lead of a lean team.

## What I work on

At [LigueLead](https://liguelead.com.br) I work on the backend of a communication platform (SMS, RCS and voice) that has handled over 100 million SMS in 2026, peaking above 20 million per month:

- Serverless dispatch pipeline on AWS Lambda, SQS, DynamoDB and Redis
- Billing migrated to a wallet service, with idempotent per-send reserve-and-capture
- Provider integrations with timeouts, retries and automatic RCS → SMS fallback
- Customer webhooks with exponential backoff, a dead-letter queue and delivery IDs
- Real-time campaign monitoring: Redis event streams, an internal API and a React back-office dashboard
- Observability in Datadog, plus an internal structured-logging SDK

Most of this lives in private repositories: the contribution graph counts it, the repository list doesn't.

## AI-assisted engineering

AI has been part of my daily work since 2025, starting with GitHub Copilot as an in-editor assistant (chat and inline). Today I work with coding agents (Claude Code, GitHub Copilot, Kiro) with guardrails, not as shortcuts:

- a versioned context base that generates each agent's instructions, checked in CI;
- a mandatory quality gate (lint, types, tests) after every change;
- a two-pass AI code review in which the second pass tries to refute the first.

## Public work

- [`atena`](https://github.com/NicollasFrazao/atena): an AI assistant for messaging-platform support teams. The LLM only interprets: it calls deterministic tools, and the application runs the queries, enforces RBAC, masks personal data and writes an append-only audit log. Real-time anomaly incidents, DuckDB over S3, NestJS + React, Amazon Bedrock; unit and end-to-end tests in CI.
- [`sqs-webhook-dispatcher`](https://github.com/NicollasFrazao/sqs-webhook-dispatcher): reliable webhook delivery on AWS Lambda + SQS — signed requests, exponential backoff with jitter, partial batch failures and a dead-letter queue. TypeScript, CDK, tested and in CI.
- [`@liguelead/api-sdk`](https://www.npmjs.com/package/@liguelead/api-sdk): the TypeScript SDK for the LigueLead API (SMS, voice, RCS, voice AI and webhooks). I created it and later rewrote it for the current API.

### Earlier work

- [`bway`](https://github.com/NicollasFrazao/bway): my Computer Engineering final project (2020), with a team of four: a Laravel shopping-list app that orders a supermarket visit by sector, using A* routes over a floor plan mapped in Python.
- [`eletrontech`](https://github.com/NicollasFrazao/eletrontech): my IT technical course final project (2015), with a team of five: electrical calculators and a canvas floor-plan editor in PHP and MySQL.
- Freelance work: [`qr-menu-ordering`](https://github.com/NicollasFrazao/qr-menu-ordering) (Laravel table ordering by QR code), [`service-order-system`](https://github.com/NicollasFrazao/service-order-system), [`lab-software-inventory`](https://github.com/NicollasFrazao/lab-software-inventory), [`pes-online-league`](https://github.com/NicollasFrazao/pes-online-league) and [`Os-Objetos-e-Suas-Narrativas`](https://github.com/NicollasFrazao/Os-Objetos-e-Suas-Narrativas) (an accessible museum guide with audio description and sign-language video).
- Hiring challenges (2021–2025), mostly Laravel: [`4yousee`](https://github.com/NicollasFrazao/4yousee-coding-challenge), [`inmediam`](https://github.com/NicollasFrazao/inmediam-coding-challenge), [`wittel`](https://github.com/NicollasFrazao/wittel-coding-challenge), [`alfasoft`](https://github.com/NicollasFrazao/alfasoft-coding-challenge), [`ironfence`](https://github.com/NicollasFrazao/ironfence-coding-challenge), [`bussolasocial`](https://github.com/NicollasFrazao/bussolasocial-coding-challenge), [`spoten`](https://github.com/NicollasFrazao/spoten-coding-challenge), [`escribo`](https://github.com/NicollasFrazao/escribo-coding-challenge), [`fidelity`](https://github.com/NicollasFrazao/fidelity-coding-challenge) and [`montink`](https://github.com/NicollasFrazao/montink-coding-challenge).
- Early personal projects: [`LEX`](https://github.com/NicollasFrazao/LEX), a vocabulary game in PHP.

## Stack

Node.js · TypeScript · AWS (Lambda, SQS, DynamoDB, S3, Firehose) · Redis · MySQL · PostgreSQL · Express · React · PHP · Laravel · Docker · Jest · PHPUnit · Datadog · GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/nicollasfrazao/) · nicollasfrazao@hotmail.com
