
# Retrieval Augmented Reasoning for Question Answering in Legal Domain

# Project Abstract
The dynamic nature of legal systems presents a fundamental challenge for artificial intelligence applications in law: legislation evolves continuously, creating a vast ever-changing corpus of legal knowledge. While large flagship language models have the capacity to absorb comprehensive legal knowledge, their development typically occurs outside the purview of legal experts, resulting in improvements that are substantial yet unpredictable in nature and alignment with legal reasoning requirements. 

In this project we addresses the critical need for robust, maintainable approaches to legal question answering by systematically evaluating retrieval-augmented generation (RAG) methods for complex legal question answering tasks that require reasoning and synthesis of information from multiple legal documents. We (1) Perform assessment of various retrieve-and-answer-question solutions that do not require model retraining on three recent multi-hop reasoning legal datasets: BarExamQA and HousingStatuteQA, and the English version of KOBLEX dataset. (2) Examine applicability of search inference-time scaling methods that perform multi-step retrieval and reasoning to legal domain and assess if the same scaling strategies are applicable across tasks and datasets.

## Roadmap

- Ingest and analyze BarExamQA, HousingStatuteQA, and KOBLEX (english) datasets.  
    - HousingStatuteQA (completed)
    - BarExamQA (completed)
    - KOBLEX english (completed)
- Establish baselines for retrieval (vanilla RAG, RAG with query expansion) and QA performance
    - HousingStatuteQA (completed)
    - BarExamQA (in progress)
    - KOBLEX english (in progress)
- Analyze dependencies between
    - Query expansion methods and embedding models (in progress)
    - QA and retrieval performances
- Implement and test baseline inference-time scaling RAG+reasoning algorithms 
    - RAG-Star, MCTS RAG
- Analyze impact of action sets and rewards on retrieval and end-to-end performance   

## Project Document
[![Button Text](img.shields.io)](https://github.com/luka-rozgic/legal-retrieval-QA/blob/main/RAGReasoningQAProject.pdf)
