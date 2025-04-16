# 📝 Essay Writer AI Agent (LangGraph + LangChain)

This project implements an automated essay writer powered by **LangChain**, **LangGraph**, and **OpenAI GPT-3.5** models. It guides the user from initial topic input to final polished essay via structured nodes and iterative refinement.

### 🚀 Key Features

- ✍️ **Essay Planning**: Generates a structured outline using GPT.
- 🔎 **Automated Research**: Integrates with Tavily to search for contextual content.
- 🧠 **Essay Generation**: Writes full 5-paragraph essays based on plan and research.
- 🧑‍🏫 **Critique + Feedback Loop**: Evaluates essays with teacher-like feedback for revision.
- 🔁 **Iterative Revisions**: Improves draft quality with every feedback cycle, capped by `max_revisions`.

### 📦 Stack Used

- **LangGraph**: For state graph orchestration
- **LangChain + OpenAI**: For LLM interactions
- **Tavily API**: To fetch real-time research
- **SQLite Memory Checkpointing**: For state persistence across revisions

### 💡 Example Task

> *"What is the difference between LangChain and LangSmith?"*

The agent will:
1. Plan the essay
2. Research the topic
3. Generate a draft
4. Critique the essay
5. Repeat the loop up to 2 times

---

### 📄 Setup

```bash
pip install -r requirements.txt
