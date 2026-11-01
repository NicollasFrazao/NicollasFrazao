# Nícollas Frazão

**Senior Backend Software Engineer** · Campinas, Brazil

Backend engineer with 10+ years building production APIs and systems — currently Node.js/TypeScript on AWS, previously PHP/Laravel. Former backend Tech Lead of a 5-developer team.

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

- [`sqs-webhook-dispatcher`](https://github.com/NicollasFrazao/sqs-webhook-dispatcher): reliable webhook delivery on AWS Lambda + SQS — signed requests, exponential backoff with jitter, partial batch failures and a dead-letter queue. TypeScript, CDK, tested and in CI.
- [`@liguelead/api-sdk`](https://www.npmjs.com/package/@liguelead/api-sdk): the TypeScript SDK for the LigueLead API (SMS, voice, RCS, voice AI and webhooks). I created it and later rewrote it for the current API.

## Stack

Node.js · TypeScript · AWS (Lambda, SQS, DynamoDB, S3, Firehose) · Redis · MySQL · PostgreSQL · Express · React · PHP · Laravel · Docker · Jest · PHPUnit · Datadog · GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/nicollasfrazao/) · nicollasfrazao@hotmail.com
