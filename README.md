# AI Agent Builder & Deployment Platform (prototype)

A clickable prototype of a no-code platform where companies build AI agents from their own knowledge and publish them as a chat widget or a standalone app.

**Live demo:** add your GitHub Pages link here

## What you can do

1. **Create an account** and sign in.
2. **Build shared libraries** that all agents can use:
   - **Knowledge bases**: text, website links, Q&A pairs, Markdown and files.
   - **Tools**: built-in actions, your own APIs (form or OpenAPI/JSON import).
   - **MCP servers**: services connected through the Model Context Protocol.
3. **Create an agent** from a template (customer support, sales, HR or custom) and choose its type (sequential or reasoning) and language model.
4. **Connect** the knowledge bases, tools and MCP servers the agent needs.
5. **Set its behaviour**: instructions, welcome message, guardrails and human handoff.
6. **Test** it in the playground.
7. **Publish** it as:
   - a **standalone app** (full-page chat, also downloadable as one HTML file), or
   - a **website snippet** to paste before `</body>` on any website.

## Prototype limitations

- Accounts and agents are saved only in the visitor's browser (localStorage). There is no server.
- Live AI answers in the playground work only when the page is opened inside Claude. On GitHub Pages, published agents answer directly from their knowledge base and hand off to a person when they can't find an answer.
- API tools and MCP servers are simulated and return sample responses.

## Run locally

Open `index.html` in any modern browser. No build step or installation is needed.

---
Group 6 · Business Modelling and Competitive Environment · Metropolia University of Applied Sciences
