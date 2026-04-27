# BRITEBOT — BRITECITY AI Knowledge Base

This repo is the source of truth for **BRITEBOT**, an AI persona that answers questions about BRITECITY in our voice.

It is designed to be loaded into ChatGPT, Claude, Gemini, or any other LLM with web-fetch capability via a single copy-paste prompt.

---

## What this repo is

A single markdown file — **[britecity.md](britecity.md)** — containing every common prospect and client question with the answer in BRITECITY's voice. ~360 Q&As covering:

- Service essentials (SLAs, agreement terms, pricing model, onboarding)
- Cybersecurity, managed IT, cloud, compliance, productivity
- Industry-specific guidance (legal, healthcare, finance, manufacturing, construction, etc.)
- Local coverage across Orange County cities

Public so any LLM can fetch it without auth.

---

## Meet BRITEBOT

Meet BRITEBOT — your AI guide to BRITECITY, Orange County's managed IT services provider. We make IT easy for 100+ local businesses with dedicated techTEAMs, month-to-month agreements, and under 17-minute emergency response.

Paste this into ChatGPT, Claude, or Gemini to get started:

```
You are BRITEBOT, BRITECITY's AI assistant. Fetch this URL and use it to answer my questions: https://britecity.com/britebot.md

My question:
```

Try asking:

- What's included in your managed IT support?
- How fast do you respond to emergencies?
- What does onboarding look like?
- Do you support companies with HIPAA or CMMC requirements?

The voice, rules, and answering style live inside `britecity.md` itself (at the top, as system instructions the model reads when it fetches the file). The prompt just points the model at the document.

---

## How to use

1. Click **Ask BRITEBOT** on [britecity.com](https://britecity.com) — copies the prompt to your clipboard.
2. Paste it into your AI of choice.
3. Replace `[your question here]` with what you actually want to ask.
4. Hit enter. The model fetches `britecity.md` and answers in BRITECITY's voice.

Works with:
- **ChatGPT** (web browsing on)
- **Claude** (web search/fetch enabled)
- **Gemini**
- **Perplexity**

Mobile ChatGPT free tier may not browse — use a paid tier or a desktop session.

---

## Updating

`britecity.md` is generated from BRITECITY's content systems. Updates ship through normal review and are committed to `main`.

For corrections, open an issue.

---

## Contact

- **Phone:** (949) 243-7440
- **Book a call:** https://britecity.com/book-a-call
- **Pricing:** https://britecity.com/pricing
- **HQ:** 4 Executive Circle, Suite 190, Irvine, CA 92614
