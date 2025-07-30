# Building-an-agent-with-LangGraph

Here is a clean **README.md** you can use for your GitHub repository.
It describes the BaristaBot café ordering agent built with LangGraph and the Gemini API, **without mentioning any date or workshop**.

---

# BaristaBot Café Ordering Agent with LangGraph & Gemini API

This repository contains an interactive café ordering system powered by [LangGraph](https://www.langchain.com/langgraph) and the [Gemini API](https://ai.google.dev/). The agent, called **BaristaBot**, simulates a real-world café experience by allowing users to order drinks through a conversational interface.

---

 🚀 Overview

**BaristaBot** is a stateful, agentic chatbot that models an end-to-end café ordering process. It:

* Accepts orders via chat using natural language.
* Shows a dynamic menu.
* Supports order management (add, clear, confirm, place order).
* Demonstrates advanced agentic logic using LangGraph and Python.

**Key Technologies:**

* **LangGraph:** For defining and managing the application's graph-based state and control flow.
* **Gemini API:** For powerful conversational AI and function-calling.
* **LangChain:** Integration for tools, memory, and schema management.

---

 📝 Features

* **Conversational Ordering:** Order any menu item and customize drinks with modifiers (milk type, sweetness, etc.).
* **Live Menu:** Menu is stored as a function (tool); supports dynamic menu changes.
* **Order Management:** Add, clear, review, and confirm your order before final placement.
* **Graph-based Flow:** Easily extendable with more states, logic, or integrations.
* **Human-in-the-loop:** User is prompted for confirmation and corrections during the order process.

---

 📦 Repository Contents

* `baristabot_agent.ipynb` – Main notebook implementing the agent and all core features.
* `requirements.txt` – Python dependencies.
* Example images and outputs (optional).

---

 🛠️ Getting Started

 1. **Clone the repository**

```bash
git clone https://github.com/your-username/baristabot-agent.git
cd baristabot-agent
```

 2. **Install dependencies**

```bash
pip install -r requirements.txt
```

 3. Configure Gemini API Key

* Store your Gemini API key as an environment variable:
  `GOOGLE_API_KEY=your-api-key-here`
* Or set it using notebook code (see the notebook setup cell for details).

 4. Run the Notebook

* Open `baristabot_agent.ipynb` in Jupyter, Colab, or Kaggle.
* Follow the notebook steps to interact with BaristaBot and place your order!

---

 ⚙️ How It Works

* **Stateful Agent:** Defines a graph of states and transitions. Each node (e.g., chatbot, human, tools, ordering) operates on a shared state object.
* **Chatbot Node:** Handles user interaction using Gemini API and LangChain.
* **Menu Tool:** Returns the latest menu on request.
* **Order Tools:** Functions for adding to, confirming, and placing orders.
* **Human Node:** Prompts user for input at each step.
* **Graph Control:** Conditional edges manage looping, exits, and branching logic.

---

 🧑‍💻 Extending the Project

* Add more menu categories or specials.
* Integrate with external ordering or inventory APIs.
* Build a web UI using [Gradio](https://www.gradio.app/) or [Streamlit](https://streamlit.io/).
* Add payment or delivery features.
* Support multi-user or scheduled group ordering.

---

 📚 References

* [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
* [Gemini API Docs](https://ai.google.dev/)
* [LangChain](https://python.langchain.com/)

---

 📝 License

Licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

 🤝 Contributing

Contributions and suggestions are welcome! Please open issues or submit pull requests.

---

**Enjoy your coffee and coding! ☕️🤖**


