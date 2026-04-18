# 🚀 Day 4 – Tool Calling Agent

This project is part of *Day 4 of the RAG Bootcamp* by *Nunnari Academy*.

## 📌 Tasks Completed

### 🔹 Tools Implemented
- web_search(query) – Fetches real-time data using Tavily  
- summarize(text) – Generates summary using ChatOllama (llama3.2:3b)  
- notes(text) – Converts output into structured notes  

### 🔹 Manual Agent Loop
- LLM selects tool using JSON format  
- Code executes the tool  
- Output is fed back to LLM  
- Continues until final answer  

### 🔹 Test Queries
- Latest news → web_search  
- Paragraph summary → summarize  
- News + summary → Tool chaining (web_search → summarize)  

### 🔹 Bonus
- Implemented ReAct Agent using LangGraph  

## 💡 Key Takeaway
Tool calling allows AI to *act using functions*, not just respond.

## 📁 File
day4_tool_calling.py

---

## 🙌 Acknowledgement
*Nunnari Academy – RAG Bootcamp*
