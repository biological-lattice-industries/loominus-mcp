# 🧪 Example Workflows – Loominus MCP

Here are starter workflows to show what's possible with Loominus MCP. Each one is self-hosted, no-code, and built with real MCP-compatible nodes.

---

## 📚 1. Research Assistant – "PDF Insight Agent"

**Goal:** Parse a directory of PDFs, extract insights, and summarize using an LLM.

**Highlights:**
- Uses local PDF reader tool (e.g. PaperMiner MCP)
- Runs queries with OpenAI or Claude via user-configured API key
- Summarizes into Markdown or JSON

**Node Flow:**
```
[Folder Input] → [PDF Reader Node] → [RAG Embedder + Retriever] → [LLM Summarizer] → [File Output]
```

**Use Cases:**
- Literature review
- Weekly paper summaries
- Digest from internal documents

→ `examples/pdf_insight_agent.json`

---

## 🔬 2. Lab Automation – "Smart Bioprint Trigger"

**Goal:** Use sensor input (e.g., temp/humidity) to determine if 3D bioprinting should begin.

**Highlights:**
- Hardware input via MCP-compatible sensor interface
- Simple rule-based or LLM-based logic
- Triggers command to BioLoom printer

**Node Flow:**
```
[Sensor Input Node] → [Condition Check or LLM Decision] → [Printer Command Node] → [Logger]
```

**Use Cases:**
- DIY lab automation
- Environment-triggered fabrication
- Closed-loop workflows with Loominus Automation

→ `examples/bioprint_trigger.yaml`

---

## 🧠 3. Multi-Agent System – "Scientific Debate Bot"

**Goal:** Run 2 agents with different personalities debating a scientific hypothesis, then summarize.

**Highlights:**
- Each agent has its own LLM config + memory
- Context sharing enabled across turns
- Summarizer agent distills the result

**Node Flow:**
```
[Agent A] ←→ [Agent B]
        ↘       ↙
       [Summary Agent]
```

**Use Cases:**
- Hypothesis evaluation
- Comparative reasoning between agents
- Human-in-the-loop scientific review

→ `examples/debate_bot.json`

---

## 📁 Want to Add Yours?

We welcome contributions of:
- Research tools
- Scientific workflows
- Creative AI automations

→ [Submit yours](https://github.com/BioLattice/loominus-mcp/discussions/categories/show-and-tell)  
→ Or add to `/examples/` and open a PR

Let's build a library of agentic tools together 🚀

