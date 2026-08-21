# Python Discombobulator

Part of [AppADay](https://augustineiacopelli.github.io/appaday/) by Augustine Iacopelli.

Paste any Python code or a traceback and get a Claude-powered explanation. Choose the depth (summary or line by line), the audience level (beginner, intermediate, or terse), and whether you're explaining working code or debugging an error. The app auto-detects whether your paste looks like a traceback and offers to switch modes, but never forces the switch.

## Features

- Syntax-highlighted input editor (highlight.js, Python language pack) with a live overlay that mirrors scroll position exactly
- Granularity toggle: high-level summary vs line-by-line walkthrough
- Audience selector: beginner, intermediate, or terse
- Mode toggle: code explanation vs traceback diagnosis, with soft auto-detection
- Settings modal for your own Anthropic API key and an optional session label, stored only in your browser's local storage

## Tech

Single-file vanilla HTML, CSS, and JavaScript. No build step, no framework. Talks directly to the Anthropic Messages API from the browser using your own API key.

## Use

Open the live page, click the gear icon, paste in your Anthropic API key, then paste code or a traceback and hit Explain It.

Live: https://augustineiacopelli.github.io/appaday-106-python-discombobulator/
