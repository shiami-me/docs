---
description: How does the magic happen?
---

# Architecture

Shiami is built upon a modified version of ZerePy.

You can check our ZerePy Implementation at  [https://github.com/shiami-me/ZerePy](https://github.com/shiami-me/ZerePy)

### Backend Infrastructure -&#x20;

1. Built upon ZerePy (Fast API based server)
2. Hosted using a cloudflare tunnel

### LLMs -

1. Completely based on Langgraph, We created our own versions of prebuilt libraries available in the langgraph package.
2. Currently, we use Gemini as our LLM
3. FAISS - For vector stores

### Frontend -&#x20;

1. Next JS + Tailwind + Shadcn/UI
2. Also uses several animation packages such as GSAP
