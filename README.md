# Working-with-IBM-Granite
A Google Colab notebook demonstrating how to implement and interact with the IBM Granite LLM using Python, built alongside the IBM SkillsBuild program.
# 🚀 Exploring IBM Granite LLM in Google Colab

This repository contains a Google Colab notebook demonstrating how to interface with and utilize the **IBM Granite** Large Language Model (LLM). Built as a hands-on extension of my learning path through **IBM SkillsBuild**, this project moves from the theoretical mechanics of foundation models into practical, programmatic implementation.

## 📌 Project Overview
The core objective of this project is to implement a clean workflow for interacting with IBM's enterprise-grade foundation models via API, applying advanced prompt engineering techniques directly in python.

Key focuses include:
- Establishing a secure connection to the model endpoint.
- Building a reusable generation function using Python.
- Implementing advanced prompting frameworks (e.g., system roles, few-shot constraints).

## 🛠️ Tech Stack & Tools
- **Language:** Python 3.x
- **Environment:** Google Colab
- **Model:** IBM Granite Family
- **API/Libraries:** `requests` / official IBM library wrappers (depending on your exact connection method)

## 🎯 Implementation Highlights

### 1. Model Connection & Environment
Successfully configured the environment variables within Colab to securely handle API keys without exposing sensitive credentials in the raw code.

### 2. Prompt Optimization
Implemented structured templates to enforce strict constraints on the model's outputs. Tested various prompting frameworks learned during the SkillsBuild modules, significantly reducing hallucinations and improving context adherence.

### 3. Output Analysis
Evaluated response generation times (latency) and formatting accuracy across different text generation and instruction tasks.

