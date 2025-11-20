# LangGraph Tutorial (Updated Code)

Updated code for Tech With Tim’s YouTube video  
(**LangGraph Tutorial - How to Build Advanced AI Agent Systems** - Tech With Tim)[https://youtu.be/1w5cCXlh7JQ]:contentReference[oaicite:0]{index=0} 

The original example code lives here:  
- Original repo: https://github.com/techwithtim/LangGraph-Tutorial :contentReference[oaicite:1]{index=1}  
- This repo (updated code): https://github.com/nickfinch71/Langchain-Tutorial  

The goal of this repository is to provide a working, up-to-date version of the tutorial code that runs against modern versions of:

- [LangGraph](https://github.com/langchain-ai/langgraph) (v1.x) :contentReference[oaicite:2]{index=2}  
- [LangChain](https://github.com/langchain-ai/langchain) (v1.x) :contentReference[oaicite:3]{index=3}  
- [langchain-openai](https://pypi.org/project/langchain-openai/) :contentReference[oaicite:4]{index=4}  

---

## What this repository contains

- A **single Python script** (`main.py`) that builds and runs the LangGraph agent from the video.
- A **`pyproject.toml`** file defining the Python package and dependencies.
- Minor adjustments to keep the code compatible with current LangGraph / LangChain APIs (v1+).

If you want to follow along with the video step-by-step, use this repo as a starting point instead of the original one whenever the APIs differ from what Tim shows.

---

## Requirements

- Python **3.11 or 3.12** is recommended (LangChain ecosystem officially supports 3.11–3.13). :contentReference[oaicite:5]{index=5}  
- An OpenAI API key (or compatible LLM provider) if you want to run the agent as in the tutorial.

You can get an OpenAI API key from your OpenAI account dashboard and set it as an environment variable.

---

## Installation

Clone this repository:

```bash
git clone https://github.com/nickfinch71/Langchain-Tutorial.git
cd Langchain-Tutorial

