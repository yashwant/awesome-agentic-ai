# 🧠 Awesome Agentic AI

Welcome to **Awesome Agentic AI** – your go-to guide for understanding, learning, and building intelligent agent-based systems with LLMs. Whether you're a curious developer, researcher, or enthusiast, this repository will help you get started and dive deep into the world of **Agentic AI**.

---

## 📌 Table of Contents

1. [What is Agentic AI?](#what-is-agentic-ai)
2. [AI Agents vs Agentic AI](#ai-agents-vs-agentic-ai)
3. [Architectures in Agentic AI](#architectures-in-agentic-ai)
4. [Frameworks for Agentic AI](#frameworks-for-agentic-ai)
5. [Latest Research Papers](#latest-research-papers)
6. [Learning Resources](#learning-resources)
7. [Roadmap to Building Agentic AI Applications](#roadmap-to-building-agentic-ai-applications)
8. [Contributing](#contributing)
9. [License](#license)

---

## 🧩 What is Agentic AI?

**Agentic AI** refers to the use of autonomous agents powered by large language models (LLMs) that can perceive, reason, plan, act, and learn in order to achieve complex goals over time.

Unlike traditional LLM applications that simply respond to a prompt, agentic AI enables:

- **Goal-directed behavior**
- **Memory and learning over time**
- **Autonomous decision-making**
- **Multi-step tool usage**
- **Environment interaction**

This paradigm shift enables a new class of intelligent systems capable of performing complex tasks like research, automation, decision support, and software orchestration.

---

## 🤖 AI Agents vs Agentic AI

| Feature                     | Traditional AI Agents       | Agentic AI                         |
|----------------------------|-----------------------------|------------------------------------|
| Reasoning                  | Rule-based or symbolic      | LLM-powered, chain-of-thought      |
| Autonomy                   | Limited to task scope       | High autonomy with reflection      |
| Learning                   | Pre-programmed or offline   | Continuous, online through memory  |
| Tools & APIs               | Often manual integration    | Dynamic and automatic use          |
| Adaptability               | Low                         | High, through LLMs and planning    |
| Communication              | Simple, command-response    | Rich, conversational planning      |

---

## 🏗️ Architectures in Agentic AI

Below are popular architectural patterns used in Agentic AI:

### 1. **ReAct (Reason + Act)**
- Interleaves reasoning and action steps.
- Agents think aloud before taking action.
- [Paper](https://arxiv.org/abs/2210.03629)

### 2. **AutoGPT / BabyAGI Style**
- Autonomous loop of planning → executing → evaluating.
- Use memory to retain state across iterations.
- Use vector DBs and toolkits.

### 3. **Plan-and-Execute**
- Agent creates a structured plan first.
- Executes each step individually or assigns to sub-agents.

### 4. **Hierarchical Agents**
- Supervisor agent coordinates specialized sub-agents.
- Great for modular, complex workflows.

### 5. **Multi-Agent Systems**
- Agents communicate with each other to collaborate on tasks.
- Useful in simulations and research environments.

---

## 🧰 Frameworks for Agentic AI

| Framework         | Description                                                                 | Link |
|------------------|-----------------------------------------------------------------------------|------|
| **LangChain**     | Modular framework for chaining LLM reasoning, memory, tools, agents        | [🔗](https://github.com/langchain-ai/langchain) |
| **Autogen (MSR)** | Multi-agent orchestration with LLMs and user agents                        | [🔗](https://github.com/microsoft/autogen) |
| **CrewAI**        | Simple multi-agent orchestration with roles and tasks                      | [🔗](https://github.com/joaomdmoura/crewAI) |
| **MetaGPT**       | Build software engineering agents that collaborate                         | [🔗](https://github.com/geekan/MetaGPT) |
| **OpenAgents**    | Agentic ecosystem for building practical agents                            | [🔗](https://github.com/OpenAgentsInc/OpenAgents) |
| **AgentScope**    | Framework from Alibaba for multi-agent collaboration                       | [🔗](https://github.com/modelscope/agentscope) |
| **Camel-AI**      | Role-playing agents that negotiate and solve problems                      | [🔗](https://github.com/lightaime/camel) |
| **SuperAGI**      | Production-ready Agentic AI platform with GUI                              | [🔗](https://github.com/TransformerOptimus/SuperAGI) |

---

## 📚 Latest Research Papers

- **ReAct: Synergizing Reasoning and Acting in Language Models** – [arXiv:2210.03629](https://arxiv.org/abs/2210.03629)
- **AutoGPT: Building Autonomous Agents with GPT-4** – [GitHub](https://github.com/Torantulino/Auto-GPT)
- **Toolformer: Language Models Can Teach Themselves to Use Tools** – [arXiv:2302.04761](https://arxiv.org/abs/2302.04761)
- **Reflexion: Language Agents with Verbal Reinforcement Learning** – [arXiv:2303.11366](https://arxiv.org/abs/2303.11366)
- **AgentVerse: A Framework for Benchmarking Multi-Agent Systems** – [arXiv:2305.14325](https://arxiv.org/abs/2305.14325)
- **CAMEL: Communicative Agents for Mind Exploration of Large Scale Language Model Society** – [arXiv:2303.17760](https://arxiv.org/abs/2303.17760)

> ✨ Want more? Check out the [Awesome LLM Agents](https://github.com/gojiteji/awesome-llm-agents) list.

---

## 📘 Learning Resources

### Blogs & Articles
- [LangChain Blog](https://blog.langchain.dev/)
- [Microsoft Autogen Tutorials](https://microsoft.github.io/autogen/)
- [Lil'Log on LLM Agents](https://lilianweng.github.io/)

### Courses
- [LangGraph Agent Workshop](https://docs.langgraph.dev/workshops/)
- [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/)
- [DeepLearning.AI LLM Specialization](https://www.deeplearning.ai/courses/)

### Videos
- [Agentic Workflows - LangChain Dev Day](https://www.youtube.com/watch?v=bXxvmXkDsrM)
- [LLM Agent Architectures Explained](https://www.youtube.com/watch?v=9JpVI0rnlok)

---

## 🛠️ Roadmap to Building Agentic AI Applications

### 🟢 Beginner
- Understand how LLMs work (Prompting, few-shot, CoT)
- Learn tool usage and chaining using LangChain or LlamaIndex
- Build simple single-agent apps with tools

### 🟡 Intermediate
- Add memory (vector DB, JSON, SQL memory)
- Learn about planning & task decomposition
- Use open-source frameworks like CrewAI, AutoGen

### 🔴 Advanced
- Design multi-agent systems (CAMEL, MetaGPT)
- Integrate LLMs with external APIs & tools
- Explore fine-tuning and custom tool creation
- Benchmark & evaluate agent performance (e.g., with AgentBench)

---

## 🤝 Contributing

Want to contribute? Awesome! Please check out our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. You can:

- Add frameworks or research papers
- Improve roadmap or tutorials
- Submit examples and demos
- Report issues or suggest improvements

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> 🚀 *Let’s build the next generation of intelligent systems together!*

