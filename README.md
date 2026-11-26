# AI Token & LLM API Cost Calculator (2026)

A fast, zero-dependency browser calculator to estimate prompt token counts from raw text and compare monthly API expenses across leading Large Language Models (**GPT-4o**, **GPT-4o mini**, **Claude 3.5 Sonnet**, **Claude 3 Haiku**, **Gemini 1.5 Pro**, and **DeepSeek V3**).

👉 **Live Interactive Tool:** [https://github.io](https://valeryivch-maker.github.io/ai-token-cost-calculator/)

## Key Features
- **Instant Text-to-Token Estimator:** Paste any system prompt or context block to measure characters, word count, and estimated token volume in real time.
- **Side-by-Side Model Presets:** One-click pricing presets for OpenAI, Anthropic, Google Gemini, and DeepSeek models (updated Nov 2026).
- **Scale & Batch Simulation:** Calculate single-request cost, cost per 1,000 requests, and total monthly API spend.
- **Shareable URL Estimates:** Configure your token volume and click **Copy Estimate Link** to share pre-filled calculations via URL parameters (`?in=...&out=...&req=...`).
- **100% Client-Side & Private:** Runs entirely in vanilla HTML/CSS/JS — no prompts or API keys are ever transmitted or stored.

## URL Query Parameters (Pre-filled Scenarios)
You can link directly to custom calculation scenarios:
- `in` — Input tokens per request (e.g., `1500`)
- `out` — Output tokens per request (e.g., `500`)
- `req` — Monthly request volume (e.g., `10000`)
- `inPrice` / `outPrice` — Custom price per 1M tokens in USD

## Related Free Calculators
- [Freelance & Payment Fee Calculator](https://github.io)
- [Crypto Staking & APY Calculator](https://github.io)
- [ROAS & Ad ROI Calculator](https://github.io)
- [Compound Interest & 401(k) Calculator](https://github.io)

## License
MIT License — free for personal and commercial use.
