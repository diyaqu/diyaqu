# Diya Qu

**I'm a builder: I get curious, go deep, and build it with AI.**

I build the AI that runs a real business, and I go deep into whatever a problem needs. I've worked across operations, sales, and venture.

Most of what's here I built and run solo, on personal subscriptions, with no budget.

## AI systems I built, use every day, and keep improving

I run my client operation on these. Each one does a job I'd otherwise have to hire for, which is how I keep a full client book moving on my own.

**Self-updating CRM.** My client conversations live on WeChat, which gives you no API, so a background daemon and a Swift accessibility layer reach the data directly and Claude turns each thread into a CRM update, running 24/7 as a self-healing service I review before it commits. The board I built on top brings my WeChat and email pipelines into one view, surfaces what needs action this week, and auto-flags leads going cold so nothing slips.

**Email outreach engine.** A full LLM email pipeline that researches each company, picks the angle, drafts the email and sends it, then sequences the follow-ups and sends them on a cadence. It tracks opens and replies, and a dashboard turns that into a read on what's landing, so I'm always tightening the copy and the flow. The reliability sits in the engineering around the model: a SQLite state machine, dry-run and validation gates, and a hard cap on daily spend.

**RedNote (Xiaohongshu) lead radar.** An LLM lead-finder for a platform that bans bots: it scores posts and comments for buyer intent and surfaces the strongest to me. It stays strictly read-only behind a kill switch and an audit log, so it can never post or risk the account. And it closes the loop: the same intel feeds a writing agent that turns what's trending into posts in my voice, covers and all.

**Mei, a compliance assistant I can put in front of a client.** An LLM assistant for U.S. employment-law questions, designed around trust: it answers only from a sourced knowledge base and current .gov sources, cites every claim, refuses when it can't ground an answer, and ships only after passing a suite of real-question evals.

**The judgment underneath.** The calls I'm most deliberate about are where AI can act on its own vs. where I stay in the loop, what guardrail each one needs, and what data ever leaves my machine. It all runs on one source of truth, so a fresh chat picks up a client's full context on the spot.

## Shipped and public

**Employee Rights Tool** ([live](https://employee-rights-tool.diyaqu-contact.workers.dev/) · [code](https://github.com/diyaqu/employee-rights-tool)). A free, no-login web tool that helps a U.S. worker tell whether their situation is illegal, what to save, and how to find a lawyer. I built it after one of my posts on workers' rights took off and the comments made the need impossible to ignore, so I turned the compliance knowledge I sell to employers into something that helps people on the other side of the table. Free to use, and it grows the audience I write for.

**Land of Opportunity** ([play](https://diyaqu.github.io/land-of-opportunity/) · [code](https://github.com/diyaqu/land-of-opportunity)). A dark-comedy game about how fast an American small business can die by paperwork. A half-built side project I made for fun; every rule in it is real.

## What I work with

Anthropic API and Claude Code, Python, Playwright, MCP, SQLite, Next.js and React. Comfortable with RAG, knowledge bases, and evals. I keep testing the newer agentic tools as they ship.

## Find me

- LinkedIn: https://www.linkedin.com/in/diya-qu/
- X: https://x.com/DiyaQu
- Live tool: https://employee-rights-tool.diyaqu-contact.workers.dev/
