#### LangSmith Implementation

This repository attempts to explore features of LangSmith to discover its capabilities and features. LLMOps(Large Language Model Operations) is a specialised branch of MLOps specifically designed to handle the unique challenges and requirements of managing large language models.

<img src=assets/workflow.png width=800 height=300>



Unlike ML models where models are trained from scratch, LLMs are trained on foundation models
- Need for customisation using prompt engineering, RAG and Fine-tuning
- Changes in API models are subject to regular updates, which may require users to update their software or migrate to newer models or endpoints.
- Difference in Evaluation of LLM through analysis of embeddings, evaluation through other LLMs, human feedback integration
- LLM-specific monitoring 
- Functional monitoring (token usage, cost, response time, error rates)
- Prompt monitoring (store and manage your prompts)
- Response monitoring (to detect hallucinations)

### LangSmith

- LangSmith is a unified DevOps platform for developing, collaborating, testing, deploying, and monitoring LLM applications.
- It has been built to enhance LLM workflows and alleviate bottlenecks that occur due to non-deterministic and unpredictable nature of LLM 
- It provides visibility to developers through out their LLM operations which help us to spot errors and remove performance bottlenecks in real time
