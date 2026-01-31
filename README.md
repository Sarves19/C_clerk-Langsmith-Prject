# 🧠 C Clarke Personal AI Assistant

A **LangGraph-powered personal AI assistant** that safely routes user queries to specialized AI agents such as **news analysis** and **scam detection**, with both **CLI** and **web UI** support.

This project demonstrates how to build **agentic AI workflows** using **LangGraph**, **LangChain**, and **tool-using LLM agents**.

---

## 🚀 Features

- 🔐 **Input Guardrails**
  - Blocks malicious or dangerous user input before reaching the LLM

- 🧭 **Router Agent**
  - Classifies user queries into:
    - `news`
    - `scam`
    - `general`

- 📰 **News Agent**
  - Uses **Tavily Search** to fetch live information
  - Produces neutral, summarized news responses

- 🚨 **Scam Detection Agent**
  - Analyzes messages for fraud/scam risk
  - Returns risk level (LOW / MEDIUM / HIGH)

- 🧩 **LangGraph Workflow**
  - Conditional routing between agents
  - Clear, inspectable state transitions

- 🖥️ **Multiple Interfaces**
  - Command Line Interface (CLI)
  - Web UI using **Gradio**

---

## 🏗️ Architecture Overview

