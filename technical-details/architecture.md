---
description: How does the magic happen?
icon: map
---

# Architecture

Shiami is built upon a modified version of ZerePy.

You can check our ZerePy Implementation at  [https://github.com/shiami-me/ZerePy](https://github.com/shiami-me/ZerePy)

### Backend Infrastructure -&#x20;

1. Built upon ZerePy (Fast API based server)
2. Hosted using a cloudflare tunnel



### Key Modifications made in the ZerePy package

1. Revamped the whole project structure to use langgraph.
2. Created specific tools for all the integrations.
3. Integrated TogetherAI, Debridge, SIlo Finance, SonicScan into ZerePy Connections

### LLMs -

1. Completely based on Langgraph, We created our own versions of prebuilt libraries available in the langgraph package.
2. Currently, we use Gemini as our LLM
3. FAISS - For vector stores

### Frontend -&#x20;

1. Next JS + Tailwind + Shadcn/UI
2. Also uses several animation packages such as GSAP

### Balancer Utils Backend -

We had to make this specifically for beets, to interact with the GraphQL API provided by Beets.fi

Built using ExpressJS

### Additional Tools Used -

1. Privy For Delegated Actions using Agent Workflows.
2. TogetherAI for image generation.
3. Browser Use for the web search mode.
