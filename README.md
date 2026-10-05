# SWE / Enginuity — CustomGPT.ai Betty-displacement demo

Sales demo replica for **Society of Women Engineers**. Not affiliated with or endorsed by SWE.

## Three surfaces (required)

1. **Floating live chat** — `js/main.js` loads `chat.js` using `DEMO_CONFIG.p_id` / `p_key`
2. **Full-page assistant** — hero button **"Try Enginuity AI assistant"** → `assistant.html` (embed.js)
3. **Header SGE search** — AI search bar → dropdown `#customgpt_search` via `sge.js`

## Open locally

```bash
cd /workspace/betty-demos/swe/demo-site
python3 -m http.server 8080
```

Then open http://localhost:8080/ (and http://localhost:8080/assistant.html).

## Wire agents

Edit `config.js` and replace `PENDING` with public embed keys:

- `p_id` / `p_key` — chat agent (floating bubble + assistant.html)
- `search_p_id` / `search_p_key` — search/SGE agent

Or pass query overrides: `?p_id=...&p_key=...&search_p_id=...&search_p_key=...`

## CTA URL notes

- Provisional (curl timed out / blocked): https://swe.org/membership/
- Provisional: https://swe.org/events/
- Provisional: https://swe.org/scholarships/
- Provisional: https://swe.org/volunteer/
- Research path: https://www.swe.org/enginuity/
- Homepage seed: https://www.swe.org/

## Brand

Primary: `#6B2D7B` · Accent: `#F5A623` · Seed: https://www.swe.org/
