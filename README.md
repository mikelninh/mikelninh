# Mikel Ninh

**AI engineer building tools for people who need them most.**

Berlin. Available for AI engineering roles and contracts.

---

## Currently shipping

|     | What it does | Stack |
| --- | --- | --- |
| [**SafeVoice**](https://github.com/mikelninh/safevoice) | Legal-AI for victims of digital harassment. Classifies a hate comment under German criminal law and generates a court-ready Strafanzeige in 30 seconds. Beta, in pilot with NGO partners. | FastAPI · SQLAlchemy · OpenAI `gpt-4o-mini` · Pydantic Structured Outputs · React · Vercel (Frankfurt) |
| [**GitLaw**](https://github.com/mikelninh/gitlaw) | AI search across 5,936 German laws. Free Bürger version live; **GitLaw Pro** is the paid tier for lawyers — case-bound research, Mandanten-Portal (DE / VI), digital power of attorney. First pilot with a Berlin law firm. | FastAPI · FAISS · OpenAI Structured Outputs · React |
| [**Digital Democracy Studio**](https://github.com/mikelninh/digital-democracy-studio) | Civic-AI closing the gap between rights on paper and rights in life: **FairEint** (evidence-based policy reform + 23-persona simulator), **Public Money Mirror** (where tax money goes — federal-budget anomaly detection), and a family of no-API-key **MCP servers** (AGB-check §305 ff. BGB, Elterngeld, Wohngeld, EU flight rights). | Python · MCP · FastAPI · OpenAI Structured Outputs |

---

## How I work

I build for victims of digital violence, citizens navigating legal systems, and people stuck in avoidable uncertainty.

Technically: FastAPI + SQLAlchemy + Alembic backends on Vercel Functions (Frankfurt region for DSGVO). OpenAI `gpt-4o-mini` with Pydantic Structured Outputs — the model literally can't return a value outside the enum. FAISS for local vector search. SHA-256 hash chains where evidence integrity matters.

Status is honest: SafeVoice and GitLaw are MVPs in active pilot, not finished products. The goal — and the work — is real users in real contexts (German lawyers, NGOs like HateAid). Open source where it helps trust.

---

## Open to work

Actively available for **AI engineering roles and contracts** — Berlin-based or remote.

Portfolio: **[mikelninh.github.io](https://mikelninh.github.io/)**

Reach me at [mikel_ninh@yahoo.de](mailto:mikel_ninh@yahoo.de) or DM [@mikelninh](https://x.com/mikelninh) on X.

---

## Also in the workshop

- [**civic-ai-mcp-toolkit**](https://github.com/mikelninh/civic-ai-mcp-toolkit) — the shared engine behind every MCP server above: server factory, `@traced`, structured logging, fixture loader, scaffolder CLI.
- [**INCA Claims-Loop**](https://mikelninh.github.io/inca-site/) — a runnable agent loop (three agents, a receipt per decision, an eval harness), built as a job application you can touch.
- [**FairEint**](https://github.com/mikelninh/faireint) & [**Public Money Mirror**](https://github.com/mikelninh/Public-Money-Mirror) — the democracy half of the studio: *what should Germany do differently?* and *where is our tax money going?*
