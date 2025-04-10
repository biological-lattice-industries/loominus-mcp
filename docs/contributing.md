# 🤝 Contributing to Loominus MCP

We're building Loominus MCP as a **community-first, agentic workflow ecosystem.**

You can contribute even if you're not a developer — by sharing ideas, tools, examples, or feedback. Here's how:

---

## 📁 1. Contribute a Node Pack

Node packs are reusable components that plug into the visual Loominus canvas.

Each pack should include:

```yaml
- name: "Node Name"
  type: "agent | tool | memory | input | output"
  description: "What it does"
  inputs: ["text", "context", "file"]
  outputs: ["string", "json", "action"]
  config: "YAML or JSON-based config with fields"
```

🧩 Recommended: Put each node as a folder inside `/nodes/your-pack-name/`

> Not sure how to start? Fork the [example-node-pack](https://github.com/BioLattice/loominus-mcp/tree/main/nodes/example-pack)

---

## 🧪 2. Share a Workflow

Workflows are `.json` or `.yaml` visual graph files built using Loominus MCP.

You can:

- 📚 Publish a cool automation or research agent
- 🛠️ Build a toolchain around a specific MCP server
- 🧠 Share a creative experiment (e.g. agent debate, real-world automation)

Submit them to:
- `/examples/your-workflow-name.json`
- Or via [Show & Tell Discussions](https://github.com/BioLattice/loominus-mcp/discussions/categories/show-and-tell)

---

## 🌐 3. Submit Your MCP Server

If you've built a custom MCP tool/server:

- Add it to [`community-servers.md`](./community-servers.md)
- Include tags, GitHub link, and a short description
- Optionally include a sample node config or workflow

---

## 🧠 4. Suggest Features or Report Bugs

Use GitHub Issues to:

- 📌 Report bugs (desktop, node engine, workflow execution)
- 💡 Request features (e.g., memory types, LLM routing, export formats)
- 🔄 Propose architectural improvements

→ [Create an Issue](https://github.com/BioLattice/loominus-mcp/issues)

---

## 👥 5. Join the Community

- 💬 Jump into [GitHub Discussions](https://github.com/BioLattice/loominus-mcp/discussions)
- 🧠 Attend monthly demo days + roadmap previews
- 🎁 Access private beta drops + node releases
- 🗣️ Help shape our direction — one idea at a time

We believe in open modular systems, agentic tooling, and visual-first automation.

Let’s build this ecosystem together. 🌍

