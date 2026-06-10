# Max Baluev

> **Founding / Staff AI engineer.** I build self-improving AI systems on the hard primitives —
> late-interaction retrieval, agent memory, and reinforcement-style credit assignment — and ship the code that proves them.

Most AI forgets. A model scores 90% today and 90% tomorrow; what worked, what failed, and what to avoid is generated and thrown away. I work on the opposite: systems whose **judgment compounds from reality** — that get sharper with use because outcomes are *scored* and *bound* to the next decision.

That thesis is **[Accreted Intelligence](https://github.com/maxbaluev/accreted-intelligence)**. The repos below are the primitives it's built on — each shippable on its own.

### 🧭 Selected work — the primitives, in the open

| Repo | What it proves |
|---|---|
| **[accreted-intelligence](https://github.com/maxbaluev/accreted-intelligence)** | The thesis + whitepaper: a Recursive Language Model over late-interaction scored-token memory, where the model is a replaceable processor and judgment lives in scored state. |
| **[maxsim-rs](https://github.com/maxbaluev/maxsim-rs)** | ColBERT-style late-interaction **MaxSim**, in clean zero-dependency Rust — the retrieval primitive, done right. |
| **[colpali-retrieve](https://github.com/maxbaluev/colpali-retrieve)** | **Multimodal** late interaction — a text query retrieves over *document-page images* by patch-level MaxSim (ColPali-style). |
| **[scored-rerank](https://github.com/maxbaluev/scored-rerank)** | Ranking that **learns from outcomes** — Beta-Bernoulli posteriors + Thompson sampling rank by what reality confirmed, not just base similarity. |
| **[mcp-retrieve](https://github.com/maxbaluev/mcp-retrieve)** | An **MCP server** exposing late-interaction retrieval as an agent tool — retrieval where agents actually consume it. |

### 🛠 What I work in
Late interaction (ColBERT · ColPali · MaxSim) · Recursive Language Models · RL credit assignment · agent memory · MCP · DSPy · Rust · Python · retrieval / RAG systems

### 📂 Background
- **acc4 / Accreted Intelligence** — self-improving agent memory: late-interaction retrieval + outcome-credited posteriors, an owner-authority floor, two reasoners over one substrate.
- **AMAI** — co-founder / CTO. Real-time emotional text-to-speech.
- **Inita** — chat-based AI automating website / CRM / ads for SMBs (DSPy + MCP).
- **Teleport** — peer-to-peer WebRTC CDN.

### 🤝 Now
Exploring **Staff / Principal / Founding AI Engineer** roles (remote) in retrieval, agent memory, and RL-for-LLMs.

📫 maxbaluev@outlook.com · [Telegram](https://t.me/maxbaluev)
