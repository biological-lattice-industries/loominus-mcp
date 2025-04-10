# 🌐 Community MCP Server Directory

This is a growing list of **Model Context Protocol (MCP)** tools and servers contributed by the Loominus MCP community.

Use these to build powerful agentic workflows with the Loominus visual builder.

---

## 📥 How to Add Yours

1. Fork this repo or open a PR
2. Add your MCP server entry below (see format)
3. Share example workflows or node packs if available
4. Tag us in [GitHub Discussions](https://github.com/BioLattice/loominus-mcp/discussions)

We welcome open source, local-hosted, and even private/enterprise MCP endpoints (with appropriate licensing).

---

## ✅ Server Entry Format

```yaml
- name: "Toolname Agent Server"
  maintainer: "@username or org"
  type: "agent | tool | memory | context | orchestrator"
  repo: "https://github.com/your-repo"
  description: "Short sentence about what this does."
  tags: ["rag", "local-llm", "science", "api", "iot"]
```

---

## 🗂️ Contributed MCP Servers

```yaml
- name: "PaperMiner"
  maintainer: "@openresearchlab"
  type: "tool"
  repo: "https://github.com/openresearchlab/paperminer-mcp"
  description: "An MCP tool for literature mining across PDFs and scientific corpora."
  tags: ["rag", "research", "nlp"]

- name: "SenseAI"
  maintainer: "@iot-hackers"
  type: "agent"
  repo: "https://github.com/iot-hackers/senseai"
  description: "Autonomous agent that interfaces with local sensors and logs data."
  tags: ["iot", "agent", "lab"]

- name: "LLM-Router"
  maintainer: "@multiagent-org"
  type: "orchestrator"
  repo: "https://github.com/multiagent-org/llm-router"
  description: "Dynamic router that distributes prompts and context across multiple LLMs."
  tags: ["multiagent", "openai", "llama", "coordination"]
```

---

## 🧠 Want to Contribute?

- Add your MCP tool by PR or submit it in the [Community Showcase](https://github.com/BioLattice/loominus-mcp/discussions/categories/show-and-tell)
- Suggest tags or feature integrations
- Create a demo workflow using Loominus MCP and link it here

---

## 🧩 Bonus: Coming Soon

- ⭐ Featured node packs built on these servers
- 🧪 Verified scientific & R&D tools
- 💬 Comments + usage notes from the community

Let’s build a global graph of open, intelligent agents.

→ [Back to Project Homepage](https://yourusername.github.io/loominus-mcp/)

