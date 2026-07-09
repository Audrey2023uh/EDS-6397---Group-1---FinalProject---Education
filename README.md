# AI-Powered Teamwork & Leadership Coach for Engineering Education

> **Project Status:** 🚧 In Development

This repository contains the source code, documentation, and resources for our EDS 6397 Final Project at the University of Houston.

Our goal is to develop an AI-powered teamwork and leadership coach that provides engineering students with personalized, evidence-based coaching using Retrieval-Augmented Generation (RAG) and agent-based AI.

---

## Overview

Engineering projects are rarely completed by individuals. Successful engineering requires effective communication, collaboration, leadership, and teamwork. However, many student teams struggle with communication breakdowns, accountability, unresolved conflicts, and unclear expectations.

This project explores how Generative AI can provide scalable, personalized coaching that helps engineering students develop these essential professional skills.

Unlike a generic chatbot, our system grounds every coaching recommendation in validated research to reduce hallucinations and improve trustworthiness.

---

## Problem Statement

Personalized coaching is valuable but difficult to provide at scale because it requires significant time, expertise, and continuous engagement.

Our solution is an AI-powered coaching platform that helps engineering student teams by:

- Understanding student reflections
- Diagnosing teamwork challenges
- Retrieving evidence from trusted sources
- Generating personalized coaching recommendations
- Validating responses before presenting them to users

---

## Project Scope

The system is designed to support engineering students throughout their teamwork experience by providing evidence-based guidance for:

- Communication
- Collaboration
- Leadership
- Accountability
- Conflict Resolution
- Team Effectiveness

---

## System Architecture

```
Student Reflection
        │
        ▼
Reflection Interface
        │
        ▼
Diagnosis Agent
        │
        ▼
Evidence Retrieval Agent (RAG)
        │
        ▼
Advice Generation Agent
        │
        ▼
Validation Layer
        │
        ▼
Personalized Coaching Recommendation
```

---

## Main Features

- Multi-Agent AI Architecture
- Retrieval-Augmented Generation (RAG)
- Evidence-Based Coaching
- Personalized Recommendations
- Hallucination Reduction
- Research-Grounded Responses
- Performance Monitoring

---

## Technologies

- Python
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Agent-Based AI
- Git & GitHub

---

## Repository Structure

```
.
├── README.md
├── requirements.txt
├── docs/
├── data/
├── agents/
├── src/
├── monitoring/
├── evaluation/
├── tests/
└── report/
```

---

## Team Members & Roles

### All Team Members
- Corpus / Knowledge Base Development

### Audrey Rah
- Data Architecture
- System Performance Monitoring

### Francisco
- Advice Generation Agent

### Alex
- Project Management
- Model Evaluation

### Luija
- Reflection Interface & Workflow Design Agent

### Kashfin
- Diagnosis & Evidence Retrieval Agents (RAG)

### Roberto
- Security, Data Privacy & Reliability

---

## Expected Outcome

The final system aims to provide engineering students with personalized, research-grounded coaching that improves teamwork, leadership, communication, collaboration, and decision-making while minimizing unsupported AI-generated advice.

---

## Future Work

- Expand the knowledge base with additional validated research
- Improve personalization using long-term user profiles
- Deploy the system in educational environments
- Evaluate coaching quality through human assessment
- Enhance system scalability and monitoring

---

## Course Information

**Course:** EDS 6397 – Generative AI Final Project

**Institution:** University of Houston

---

## License

This repository was created as part of the EDS 6397 course project at the University of Houston.
