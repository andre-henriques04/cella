# 🚀 CELLA — Context-Engineered Long-Lived Agent


*Built for transparency, reliability, and next-gen agentic AI development.*


---


## ✨ Overview


**CELLA** is a modern, open-source AI agent platform inspired by the latest breakthroughs in context engineering and agentic systems (see: Cognition AI, Anthropic). 
Unlike typical multi-agent frameworks, CELLA uses a single-agent, persistent-memory architecture designed for reliability, transparency, and easy extensibility.


- 🧠 **Persistent context & memory compression:** Reliable long-running sessions, with context automatically summarized as tasks grow.
- 🔍 **Transparent agent workflow:** Every action, plan, and tool call is visualized for total clarity.
- 👤 **Human-in-the-loop controls:** Users can approve, retry, or modify the agent’s next move at any stage.
- 🛠️ **Composable tool APIs:** Easy-to-integrate modules for code execution, web search, PDF/document loading, and more.
- 🌐 **Beautiful, interactive web demo:** Live action timeline, memory inspector, session logs, and public sharing.
- ⚡ **Built for 2025 & beyond:** Context compression, Model Context Protocol (MCP), and cutting-edge best practices.


---


## 🏗️ Architecture & Stack


| Layer     | Tech / Approach                 | Purpose                                        |
|-----------|---------------------------------|------------------------------------------------|
| Frontend  | Next.js, React, Tailwind, shadcn/ui | Interactive UI, timeline, memory window         |
| Backend   | FastAPI (Python), Docker        | Agent loop, API, tool orchestration             |
| LLMs      | OpenAI GPT‑4 / Claude           | Agentic reasoning, planning, memory compression |
| Memory    | Pinecone or Weaviate (vector DB)| Store & compress long session traces            |
| Protocols | Model Context Protocol (MCP)    | Standardized tool integration                   |


---


## 🎯 Key Features


- **Single-agent, linear workflow:** Robust, serial decision-making (no multi-agent chaos).
- **Action timeline:** Visual log of every agent step, tool call, and reflection.
- **Memory inspector:** See the agent’s “mind” in real time—what it knows, plans, and compresses.
- **Human-in-the-loop:** Approve, retry, or modify any agent action.
- **Public session sharing:** Replay, export, and share agent workflows.
- **Modular tool integration:** Plug in your own tools (search, code exec, document parsers) via MCP or custom adapters.
- **Production-ready deployment:** Deployable on Vercel (frontend) and Render/Heroku (backend).


---


## 🧑‍💻 Inspiration & Best Practices


CELLA is built upon principles from:


- [Don’t Build Multi-Agents (Cognition AI)](https://cognition.ai/blog/dont-build-multi-agents#applying-the-principles) 
 _Single-threaded, context-complete agent for reliability and transparency._
- [Building Effective Agents (Anthropic)](https://www.anthropic.com/engineering/building-effective-agents) 
 _Simplicity, explicit planning, and well-documented tool integration._


---


## 🚦 Status


**MVP roadmap:** 
- [x] Repo & monorepo setup 
- [ ] Backend API (FastAPI) 
- [ ] Frontend “Hello World” 
- [ ] Agent loop & action timeline 
- [ ] Tool APIs & memory compression 
- [ ] Live demo & public deployment 
- [ ] README polish & docs


---


## 🛠️ Local Development (Quickstart)


```bash
# Clone the repo
git clone https://github.com/andre-henriques04/cella.git
cd cella


# Backend setup (Python 3.10+)
cd backend
python3 -m venv venv
source venv/bin/activate
pip install fastapi uvicorn


# Frontend setup (Node.js LTS)
cd ../frontend
npx create-next-app@latest .
npm run dev
```


---


## 🌟 License
MIT License. Use, contribute, and star the repo if you find it useful!
