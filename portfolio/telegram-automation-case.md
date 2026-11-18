# Telegram Automation Assistant — portfolio case

[Русская версия](telegram-automation-case-ru.md)

**Status (18 November 2026):** Public Telegram demo available; individual features have different verification levels. This is a self-directed portfolio project, **not a commissioned client delivery**.

**Try:** [Open the Telegram bot](https://t.me/Inna_Automation_2026_bot) and send `/demo` (market comparison), `/about` (overview), or `/start` (bilingual intake).

## Business problem

Small teams often need to collect structured requests, connect external data and turn repetitive reporting into a short, actionable summary. This demonstration combines those steps in a Telegram interface.

## Implemented design

- Bilingual English/Russian, five-question intake and consent-oriented lead workflow.
- Cached Bitcoin versus S&P 500 comparison using external market data, a chart and an AI-assisted summary.
- Cloudflare Worker backend, D1 storage and scheduled refresh to avoid triggering data/API/AI work on each visitor request.
- Input validation, bounded resource use and fallback behavior for missing data or model responses.

## Evidence and limits

- Earlier real Telegram screenshots confirmed the BTC/S&P 500 `/demo` flow and the `/about` profile buttons. This is historical evidence, not a fresh end-to-end acceptance test.
- The NYC Rat Index extension was implemented and locally tested (44/44 tests), but its corrected Cron-backfill bundle **has not been confirmed live**. Do not treat `/rats` as an accepted feature.
- No verified customer revenue, lead-conversion metrics, sales uplift or production SLA are claimed.
- Market comparisons are illustrative, **not investment advice**. Correlation is not evidence of prediction or causation.

## Transferable client deliverables

Discovery and acceptance criteria; bot conversation design; API integration; cached data pipeline; failure handling; QA and handover. Payment integrations, third-party APIs and legal/compliance requirements must be scoped separately.

**Project contact:** [Personal website](https://inna-kashtanova.com/) · [LinkedIn](https://www.linkedin.com/in/pminnaka/).

*This page is public GitHub portfolio documentation, not proof that the separate Hostinger website, LinkedIn Featured or Upwork portfolio has been updated.*
