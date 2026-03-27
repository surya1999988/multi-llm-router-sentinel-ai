<img width="800" height="1216" alt="image" src="https://github.com/user-attachments/assets/62c872e7-f55d-48c3-8bbb-00beadbebbe4" />


# Sentinel AI: Multi-LLM Router

## Overview

Sentinel AI is an intelligent multi-LLM routing system that dynamically selects the most appropriate language model for a given query. The system optimizes performance by balancing accuracy, latency, and cost across multiple models.

## Objective

To design a scalable AI system that routes user queries to different language models based on task complexity and requirements, improving efficiency while reducing computational cost.

## Tech Stack

* Python
* Large Language Models (LLMs)
* Prompt Engineering
* Routing Logic and Heuristics

## System Design

The system follows a modular pipeline:

1. Input Processing: Accepts user query
2. Query Analysis: Evaluates complexity, length, and intent
3. Routing Engine: Determines the optimal model
4. Model Execution: Sends query to selected LLM
5. Response Output: Returns generated response

## Workflow

User Query → Analysis → Routing Decision → Model Selection → Response

## Key Features

* Dynamic LLM selection
* Cost-aware decision making
* Efficient query handling
* Modular and extensible architecture

## Example Routing Logic

* Simple queries routed to lightweight models
* Complex reasoning tasks routed to advanced models
* Code-related queries routed to specialized models

## How to Run

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

## Project Structure

* `multi_llm_router.ipynb` → main implementation
* `requirements.txt` → dependencies
* `README.md` → project documentation

## Future Improvements

* Reinforcement learning-based routing
* Real-time latency and cost tracking
* API-based deployment
* Integration with production LLM services

## Author

Surya Prakash 
AI Engineer | Machine Learning Enthusiast | Building Intelligent Systems
