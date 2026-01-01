# Retrieval Augmented Reasoning for Question Answering in Legal Domain

The dynamic nature of legal systems presents a fundamental challenge for artificial intelligence applications in law: legislation evolves continuously, creating a vast and ever-changing corpus of legal knowledge. Traditional approaches that embed legal knowledge directly into model weights face significant maintenance challenges, as they require frequent retraining to remain current. While large flagship language models possess the capacity to absorb comprehensive legal knowledge, their development typically occurs outside the purview of legal experts, resulting in improvements that are substantial yet unpredictable in nature and alignment with legal reasoning requirements.

In this work we addresses the critical need for robust, maintainable approaches to legal question answering by systematically evaluating retrieval-augmented generation (RAG) methods for complex legal question answering tasks that require reasoning and synthesis of information from multiple legal documents. Our main contributions are (1) A comprehensive assessment of various retrieval and question-answering solutions that do not require model retraining on three recent multi-hop reasoning legal datasets: BarExamQA, HousingStatuteQA, and the English version of KOBLEX. (2) Introduction of a test-time compute scaling Monte Carlo Tree Search to legal domain and establishing the viability of test-time compute scaling for complex legal reasoning tasks.

## Datasets

## Results
