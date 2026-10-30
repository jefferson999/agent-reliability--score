# Agent Reliability Score v0.2

Test your AI agent in 10 minutes. No install, no API key, no account, $0.

## What is new in v0.2
- Auto-score: transparent, browser-only keyword/value rules in tasks.js suggest ticks. You review and confirm them. No AI judge, no API, nothing leaves the page.
- What to fix: every failed criterion gives a plain-language fix, for developers and non-developers.
- Compare agents: name two agents, score both, see side-by-side percentages.
- Cost per successful test, total time, history in this browser only (localStorage).
- Download tasks.json, edit it, import your own tasks. Export Markdown and JSON.
- 20 tasks: 10 developer, 5 personal life, 5 creator.

## Use it
Open index.html in a browser. Pick a category and task, give the prompt to your agent, paste its answer, click Auto-score, review the ticks, click Score this task. Export when ready.

## Why this, not DeepEval / LangSmith for a first test?
DeepEval and LangSmith are powerful for CI and production, and they win there. They take install, Python, API keys, and hours to set up. This tool takes 10 minutes, works on a phone, with no install and no data leaving the page. Use this first to find failures fast, then graduate to DeepEval for CI.

## Privacy
Runs entirely in your browser. No server, database, login, or tracking. Exported reports contain scores, not pasted answers.
