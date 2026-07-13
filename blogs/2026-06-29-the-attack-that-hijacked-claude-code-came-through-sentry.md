---
title: "The attack that hijacked Claude Code came through Sentry. Datadog, PagerDuty, and Jira have the same exposure."
url: "https://venturebeat.com/security/the-attack-that-hijacked-claude-code-came-through-sentry-datadog-pagerduty-and-jira-have-the-same-exposure"
date: "2026-06-29"
author: "louiswcolumbus@gmail.com (Louis Columbus)"
feed_url: "https://venturebeat.com/category/security/feed/"
---
A single fake error report hijacked Claude Code in controlled testing — the agent ran the attacker's code with the developer's full privileges, and not one alert fired. EDR, WAF, IAM, and the firewall all missed it completely. Tenet Security's June agentjacking disclosure describes a single crafted Sentry error event — sent through a public credential that requires no breach and no authentication — that injected attacker instructions into error data that Claude Code, Cursor, and Codex then executed as trusted diagnostic output.
