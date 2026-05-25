# llm-customer-support-agent
An AI-powered customer support workflow built using OpenAI, Pydantic, structured JSON outputs, validation retry loops, and tool calling.  The system validates customer queries, converts natural language into structured machine-readable data, and enables intelligent FAQ tool usage through OpenAI function calling.

An AI-powered customer support automation workflow built using OpenAI, Pydantic, structured JSON outputs, validation retry loops, and tool calling.

This system validates customer support queries, converts natural language into structured machine-readable data, and enables intelligent FAQ tool usage through OpenAI function calling.

---

# Features

- Structured JSON output generation
- Pydantic schema validation
- Email and order ID validation
- Validation retry/error feedback loops
- OpenAI tool/function calling
- FAQ lookup simulation
- AI-powered customer support workflow
- Production-style LLM pipeline architecture

---

# Technologies Used

- Python
- OpenAI API
- Pydantic
- JSON
- Jupyter Notebook
- Tool Calling / Function Calling
- Prompt Engineering

---

# System Architecture

```text
User Input
    ↓
LLM Prompt
    ↓
Pydantic Validation
    ↓
Retry Feedback Loop
    ↓
Structured JSON Output
    ↓
Tool Calling
    ↓
FAQ Lookup Tool
    ↓
AI Response
```

---

# Example Workflow

## User Input

```text
"I forgot my password."
```

## Structured JSON Output

```json
{
  "query": "I forgot my password.",
  "tags": ["password", "account access"]
}
```

## Tool Call

The LLM intelligently decides to call the FAQ lookup tool using structured arguments generated from the user query.

---

# Skills Demonstrated

- LLM Engineering
- AI Workflow Design
- Structured Outputs
- Pydantic Validation
- JSON Schema Enforcement
- Prompt Engineering
- AI Tool Calling
- Error Handling
- Validation Pipelines
- AI Agent Foundations

---

# Project Goals

This project was built to explore:
- reliable LLM outputs
- schema validation
- AI automation pipelines
- tool-calling architectures
- production-ready AI engineering workflows

---

# Future Improvements

- Streamlit web application
- Multi-tool orchestration
- Vector database integration
- RAG implementation
- Customer sentiment analysis
- Logging and monitoring
- Retry automation
- Agent memory systems

---

# Author 
Oluwaseyi(John) Bamigbade

John Bamigbade

AI Engineer | Data Scientist | LLM Workflow Developer
