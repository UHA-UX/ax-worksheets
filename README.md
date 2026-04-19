# AX Worksheets

AX Worksheets is a beginner-friendly worksheet pack for designers exploring Agentic Experience (AX). It introduces the fundamentals and gives product, design, and engineering teams a shared starting point for shaping agent behavior.

The project is currently published as a single static HTML file, making it easy to open locally, share internally, or publish with GitHub Pages.

## Who It's For

- Designers who are curious about AX and want a practical place to start
- Product teams aligning on how an agent should behave before writing prompts or flows
- Cross-functional teams working together on tone, limits, fallback behavior, and escalation

## What's Inside

| # | Worksheet | Purpose |
| --- | --- | --- |
| 01 | **Agent Behavior Spec** | Define who the agent is, what it can do, what it must never do, and when to escalate |
| 02 | **Clarification Question Priority Map** | For each intent type, define the single most critical question to ask first |
| 03 | **Fallback & Escalation Matrix** | Map every failure state to a designed agent response and recovery path |
| 04 | **Roleplay Scenario Deck** | Simulate the interaction from both sides before any code is written |
| 05 | **Annotated Conversation Walkthrough** | Label every design decision in a real or hypothetical conversation |

These worksheets are designed to help teams define the basics first:

- what the agent is for
- what it can and cannot do
- when it should escalate
- how it should recover from failure states
- how to evaluate conversations with intention

## Files

- `index.html`: the main worksheet pack

## Open Locally

Open `index.html` directly in a browser.

On macOS, you can also run:

```bash
open index.html
```

## Publish With GitHub Pages

Because this project is a static HTML page, it can be published easily with GitHub Pages.

1. Push the repository to GitHub.
2. In the repository settings, open Pages.
3. Set the source to deploy from the `main` branch.
4. Use the repository root (`/`) as the folder.

Once enabled, GitHub Pages will serve `index.html` automatically.

## How To Use The Pack

Use the worksheets as a collaborative starting point with PM, ENG, and UX in the same room. They are especially useful early in the process, before conversation design becomes too detailed.

A simple way to run the workshop:

1. Start with the Agent Behavior Spec.
2. Define question priorities for key user intents.
3. Fill out failure and escalation handling before implementation.
4. Roleplay realistic scenarios.
5. Review and annotate sample conversations together.

## Credits

**Yuha Kim** · AI Product Designer  
[yuha.work](https://yuha.work) · [linkedin.com/in/yuha-kim](https://linkedin.com/in/yuha-kim)
