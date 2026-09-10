# Henry Hai Nguyen

MSWE candidate at UC Irvine, graduating December 2026. I build AI automation and agentic
systems, and I ship the production Python and TypeScript underneath them.

Right now I am an AI Automation Engineer at ArtHouse Studio and a Full-Stack Engineer at
TCP, and I compete nationally for the UCI boxing team.

**Open to** fall 2026 internships and full-time roles in AI automation, agentic systems,
and full-stack engineering. US citizen, no sponsorship needed. Irvine and Milpitas, CA.

### Selected work

**[SentryQuery](https://github.com/henry-hai/SentryQuery-AI)**
Multi-agent RAG on an explicit LangGraph StateGraph. A GPT-4o Researcher routes between a
Pinecone retriever and Tavily live search, and a cost-aware gpt-4o-mini Critic verifies
every drafted claim against the exact retrieved chunks captured in graph state before the
answer reaches the user. Exposed as an MCP server, with a Pydantic output contract and a
LangSmith eval harness covering answer, tool-use, schema, and groundedness correctness.
Runs locally, not hosted.

**[Barber Booking](https://github.com/henry-hai/barber-booking)**
A booking platform I deployed end to end for a practice with 300+ clients. A static
Next.js site on Vercel calls a TypeScript Express API on Render under a custom domain,
and a password-protected React dashboard reads the data through a read-only service
account. The four-system booking contract is pinned by a CI test that runs the real code
on real payloads. Booking is also exposed to AI agents as MCP tools over that same
validated path. Live at [henryhaistudio.com](https://henryhaistudio.com).

**[arthouse-ops](https://github.com/henry-hai/arthouse-ops)**
A Python service that runs weekly on scheduled GitHub Actions, unifying about 18,800
WordPress form entries into one Google Sheet through a custom PHP REST plugin and tagging
each message by category, sentiment, and summary. It surfaces the roughly 140 messages
that actually need a person out of about 18,000. Migrated from a production workflow-tool
implementation so the guarantees became tested code. 117 tests in the suite, 107 of them
in CI.

**[AI Hairstyler](https://github.com/henry-hai/AI-Hairstyle-Recommender)**
A scikit-learn classifier trained on nine scale- and rotation-invariant geometric
features from 468 MediaPipe landmarks, benchmarked against a PyTorch neural net with
k-fold cross-validation and per-class F1. Served behind a FastAPI endpoint through one
shared feature-extraction path so training and serving cannot drift apart.

**[GrantSmith](https://github.com/henry-hai/grantsmith)**
A grant-writing assistant running a custom RAG pipeline with OpenAI embeddings and
cosine-similarity retrieval over past proposals, on a provider-agnostic LLM layer.

### Stack

Python, TypeScript, JavaScript, Java, PHP, SQL
LangGraph, MCP, RAG pipelines, multi-agent systems, scikit-learn, PyTorch
FastAPI, React, Next.js, Node.js, Express, Tailwind
AWS, GCP, Docker, Linux, GitHub Actions, Vercel, PostgreSQL

### Before software

14 years as a barber, running my own book. It is where the booking platform came from,
and it is most of what I know about shipping something people have to use every day.

### Reach me

[hhnguy10@uci.edu](mailto:hhnguy10@uci.edu) | [LinkedIn](https://www.linkedin.com/in/henryhai99)
