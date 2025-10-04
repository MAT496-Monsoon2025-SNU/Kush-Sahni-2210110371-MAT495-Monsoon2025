# LangSmith Course Notebooks Documentation

This directory contains Jupyter notebooks that demonstrate various features and capabilities of LangSmith, organized by modules.

## Module 0: RAG Application
Location: `/notebooks/module_0/`

### RAG Application (rag_application.ipynb)
- Basic implementation of a Retrieval-Augmented Generation (RAG) system
- Uses LangSmith for tracing and monitoring
- Demonstrates vector store integration for document retrieval

## Module 1: Tracing and Monitoring
Location: `/notebooks/module_1/`

### 1. Tracing Basics (tracing_basics.ipynb)
- Introduction to LangSmith tracing functionality
- Implementation of tracing decorators
- Demonstration of monitoring LLM calls and chain executions
- Setting up environment variables for LangSmith integration

### 2. Alternative Tracing Methods (alternative_tracing_methods.ipynb)
- Different approaches to implement tracing in LangChain applications
- Various tracing patterns and best practices
- Usage of different tracing decorators and their effects

### 3. Types of Runs (types_of_runs.ipynb)
- Understanding different types of runs in LangSmith
- Chain runs vs LLM runs
- Monitoring and analyzing different run types

### 4. Conversational Threads (conversational_threads.ipynb)
- Implementation of conversation tracking
- Managing conversation history
- Tracing conversational flows

## Module 2: Experiments and Evaluation
Location: `/notebooks/module_2/`

### 1. Experiments (experiments.ipynb)
Key Features Implemented:
- Model comparison experiments between GPT-4 and GPT-3.5-turbo
- Custom evaluator implementation (`is_concise_enough`)
- Dataset versioning and management
- Different experiment configurations:
  - Multiple model evaluations
  - Dataset version comparisons
  - Split-based testing
  - Specific data point testing
  - Experiment repetitions
  - Concurrent execution
  - Metadata tagging

### 2. Dataset Upload (dataset_upload.ipynb)
- Process for creating and managing datasets in LangSmith
- Data versioning capabilities
- Dataset tagging and organization

### 3. Evaluators (evaluators.ipynb)
- Implementation of custom evaluation metrics
- Integration of evaluation frameworks
- Measuring model performance

### 4. Summary Evaluators (summary_evaluators.ipynb)
- Specialized evaluators for summary generation
- Metrics for measuring summary quality

### 5. Pairwise Experiments (pairwise_experiments.ipynb)
- Comparative analysis between different models
- Head-to-head performance testing

## Key Features Across Notebooks

### Environment Setup
- Configuration of API keys
- Setting up LangSmith environment variables
- Integration with various LLM providers

### Tracing Implementation
- Decorator-based tracing
- Automated monitoring of LLM calls
- Chain execution tracking

### Evaluation Framework
- Custom evaluation metrics
- Performance comparison tools
- Dataset management and versioning

### Experimentation
- Model comparison capabilities
- A/B testing frameworks
- Concurrent execution support

## Usage Notes
1. Ensure all environment variables are properly set in `.env` file
2. Each notebook can be run independently
3. Some notebooks may require specific API keys or access tokens
4. Follow the module order for best learning experience

## Dependencies
- LangChain
- LangSmith
- OpenAI
- Other requirements as listed in `requirements.txt`