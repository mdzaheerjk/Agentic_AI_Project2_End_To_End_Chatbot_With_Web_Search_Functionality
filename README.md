# 🤖 Agentic AI Project 2: End-to-End Chatbot With Web Search Functionality

![Python](https://img.shields.io/badge/Python-3.13%2B-brightgreen)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-Chatbot-blue)
![Web Search](https://img.shields.io/badge/Web-Search-lightblue)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)

A modern, agentic end-to-end chatbot platform that combines conversational AI with web search capabilities via tool integration. This project demonstrates how to build, extend, and deploy a smart conversational assistant using modular agent design, graph-based orchestration, and seamless integration of web search tools—all wrapped in a user-friendly Streamlit UI.

> 📁 **Repository:** `Agentic_AI_Project2_End_To_End_Chatbot_With_Web_Search_Functionality`

---

## 🚀 Project Highlights

- 🧠 **Agentic AI Chatbot:** Modular chatbot architecture with agent and node abstractions.
- 🌐 **Web Search Tool Integration:** The chatbot can search the web in real-time to answer user queries.
- 🔗 **LangGraph-Oriented:** Graph-based agent orchestration for flexible, extensible workflows.
- 🖥️ **Modern Streamlit UI:** Clean, interactive user interface for chatting and displaying search results.
- 🧩 **Extensible:** Add more nodes, tools, and agent behaviors with minimal effort.

---

## 🧠 Technical Stack

- **Python 3.13+**
- **Agentic AI Patterns**
- **LangGraph-inspired graph orchestration**
- **Tool-based agent extensions (web search)**
- **Streamlit (UI)**
- **Modular agent, node, state, and tool abstractions**

---

## 🏗️ Project Structure

```bash
Agentic_AI_Project2_End_To_End_Chatbot_With_Web_Search_Functionality/
├── app.py                         # Entry point for running the chatbot app
├── requirements.txt
├── LICENSE
├── README.md
└── src/
    ├── __init__.py
    ├── langgraphagenticai/
    │   ├── __init__.py
    │   ├── LLMS/
    │   │   ├── __init__.py
    │   │   └── groqllm.py
    │   ├── graph/
    │   │   ├── __init__.py
    │   │   └── graph_builder.py
    │   ├── nodes/
    │   │   ├── __init__.py
    │   │   ├── basic_chatbot_node.py
    │   │   └── chatbot_with_Tool_node.py
    │   ├── state/
    │   │   ├── __init__.py
    │   │   └── state.py
    │   ├── tools/
    │   │   ├── __init__.py
    │   │   └── search_tool.py
    │   ├── ui/
    │   │   ├── __init__.py
    │   │   ├── main.py
    │   │   ├── display_result.py
    │   │   ├── loadui.py
    │   │   ├── uiconfigfile.py
    │   │   └── uiconfigfile.ini
    │   └── main.py
    └── __pycache__/
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Agentic_AI_Project2_End_To_End_Chatbot_With_Web_Search_Functionality.git
cd Agentic_AI_Project2_End_To_End_Chatbot_With_Web_Search_Functionality
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the chatbot (Streamlit UI)
```bash
streamlit run src/langgraphagenticai/ui/main.py
```
or run the app directly:
```bash
python app.py
```

---

## 🧪 Example Usage

- **Conversational Chatbot:**  
  Say hello, ask questions, or have a conversation—the agent responds using LLM-based logic.
- **Web Search-Enabled:**  
  Ask questions that require up-to-date information or facts; the chatbot uses its web search tool to fetch live answers.
- **User-Friendly UI:**  
  Chat, see search results, and interact via a clean Streamlit interface.

---

## 🧩 Extensibility

- **Add More Tools:**  
  Integrate additional tools (APIs, calculators, etc.) by creating new nodes and tool classes.
- **Custom Agent Logic:**  
  Modify the graph and agent state for more advanced behaviors.

---

## 📚 Documentation

See code comments and structure for details on extending the agentic graph, nodes, tools, and UI.

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. Modular, agentic chatbot with real-time web search tool
2. Clean, extensible Python codebase (add more agents, tools, UIs)
3. Streamlit UI for modern, user-friendly interaction
4. Designed for learning, research, and quick prototyping
