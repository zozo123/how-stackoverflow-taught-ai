# The Data That Taught the Machines

**An interactive deep-dive into how Stack Overflow became the foundational training data for AI coding agents — and then trained its own replacement.**

🔗 **Live:** https://zozo123.github.io/how-stackoverflow-taught-ai/

Built in the spirit of a *learn-by-dragging* sandbox (inspired by the [market-making-sandbox](https://zozo123.github.io/market-making-sandbox/)): vanilla JS, [Plotly](https://plotly.com/javascript/) & [KaTeX](https://katex.org/). No backend, no telemetry, single file.

## What's inside

A single-page interactive essay with hands-on widgets:

1. **The perfect classroom** — click through the anatomy of a Stack Overflow post and see how each part (question, code, explanation, votes) maps onto a phase of LLM training.
2. **The reward signal** — slide upvotes / toggle "accepted" and watch the StackLLaMA reward function the model is trained to maximize.
3. **The corpus** — the documented contribution of Stack Exchange to The Pile, LLaMA, InCoder, RedPajama, Dolma and StarCoder2, with the labs' own justifications.
4. **The collapse** — the famous question-volume chart (−76% since ChatGPT), from Stack Overflow's own Data Explorer, with toggles.
5. **The ouroboros** — a live model-collapse simulator (Shumailov *Nature* 2024) with a "replace vs. accumulate" switch (Gerstgrasser 2024).
6. **Mirrors & memory** — models learn culture and code; the memorization & CC BY-SA attribution problem.
7. **The historical arc** — 2008 → today in seven beats.
8. **What's next** — the incentive problem nobody has solved.
9. **Go deeper** — a curated learning path (Karpathy, fast.ai, Hugging Face, the foundational papers).
10. **Receipts** — every headline number sourced; contested and illustrative claims explicitly flagged.

See [`POST.md`](./POST.md) for the written article version, and [`SOCIAL.md`](./SOCIAL.md) for launch copy (X thread, LinkedIn, HN).

## Social cards

- `og-image.png` (1200×630) — wired into Open Graph + Twitter meta; auto-previews when the link is shared.
- `og-square.png` (1200×1200) — square variant for Instagram / Mastodon / manual posts.

Both are generated from `og.html` / `og-square.html` via headless Chrome — edit the HTML and re-render.

## Run locally

It's a single static file — just open it:

```bash
open index.html      # macOS
# or serve it:
python3 -m http.server 8080   # then visit http://localhost:8080
```

## Sourcing & honesty

Every statistic links to a primary source on the page. Figures that are contested (e.g. traffic-decline methodology, the exact peak) are tagged, and one illustrative narrative element (the "StackGPT" thought experiment) is clearly labeled as *not a verified event*. The point stands without overclaiming.

---

*Generated with [Claude Code](https://claude.com/claude-code).*
