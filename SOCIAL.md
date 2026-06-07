# Launch copy

Live: **https://zozo123.github.io/how-stackoverflow-taught-ai/**

Assets:
- `og-image.png` — 1200×630 landscape card (wired into the page's OG/Twitter meta; auto-previews on link share)
- `og-square.png` — 1200×1200 square card (for Instagram / Mastodon / manual posts)

---

## One-liner

> Stack Overflow didn't just *help* AI learn to code — it was the classroom. Then it trained its own replacement. An interactive, fully sourced deep-dive 👇
> https://zozo123.github.io/how-stackoverflow-taught-ai/

---

## X / Twitter thread

**1/**
For 15 years, developers volunteered to build the most rigorously structured dataset of programming logic in history.

Then we taught a machine to read it — and it learned to replace us.

An interactive deep-dive (drag the sliders 👇):
https://zozo123.github.io/how-stackoverflow-taught-ai/

**2/**
A Stack Overflow post is accidentally the *perfect* training example:

• question → instruction
• accepted code → completion
• the explanation → chain-of-thought
• upvotes + the green ✓ → a ready-made human-preference label

Labs otherwise pay millions to recreate each of these.

**3/**
It's not a vague claim — it's in the documented recipe of nearly every foundational model:

The Pile (5.13%), LLaMA (sorted *by vote score*), InCoder (57GB of SO), RedPajama, Dolma, StarCoder2.

RefinedWeb is the control case — it dropped curated sources on purpose.

**4/**
Then the flywheel broke.

Monthly questions: ~146k (peak, 2021) → 108,563 (ChatGPT launch) → 25,566 (Dec 2024). A 76% collapse, back to 2009 levels.

The thing trained on Stack Overflow emptied Stack Overflow's front page.

**5/**
The scary part: if new questions stop being asked in public, models start training on their own output.

*Nature* (2024) showed that leads to collapse — the rare and novel vanish first.

The site has a live simulator for this. Flip "replace" vs "accumulate" and watch.

**6/**
The unsolved problem isn't technical. It's incentives.

Why write the canonical answer to a hard bug if the next dev asks a chatbot that learned from you but never sends anyone back?

Every number is sourced; the illustrative bits are labeled. Take a look:
https://zozo123.github.io/how-stackoverflow-taught-ai/

---

## LinkedIn

**Stack Overflow didn't just help AI learn to code. It was the classroom — and then it trained its own replacement.**

I built an interactive, fully sourced deep-dive into one of the most fascinating feedback loops in tech.

The core idea: a Stack Overflow thread is accidentally the perfect format for teaching a language model. A natural-language question is an instruction. The accepted code is a completion. The explanation teaches step-by-step reasoning. And the upvotes + accepted-answer checkmark are a ready-made human-preference signal — the precursor to RLHF, donated for free over 15 years.

That's not a metaphor. Stack Exchange appears by name in the documented training recipe of The Pile, LLaMA (which literally sorted answers by vote score), InCoder, RedPajama, Dolma and StarCoder2.

Then the flywheel broke. Monthly questions fell ~76% after ChatGPT — back to 2009 levels. The tool trained on the commons quietly emptied it. And if new questions stop being asked in public, models risk training on their own output, which research links to "model collapse."

The page lets you play with all of it — a reward-function widget, the dataset breakdown, the decline chart, and a live model-collapse simulator with a "replace vs. accumulate" switch.

The open question is the one I find most interesting: how do you keep humans generating new knowledge once the machine can already answer most of what we'd have asked?

🔗 https://zozo123.github.io/how-stackoverflow-taught-ai/

Built with vanilla JS, Plotly & KaTeX. No backend, every figure sourced.

#AI #LLM #MachineLearning #SoftwareEngineering #StackOverflow

---

## Hacker News title

> Show HN: How Stack Overflow taught AI to code – an interactive, sourced deep-dive

(First comment: note it's a single static page, vanilla JS + Plotly + KaTeX, every stat links to a primary source, and the one illustrative anecdote — "StackGPT" — is explicitly labeled as not a verified event.)
