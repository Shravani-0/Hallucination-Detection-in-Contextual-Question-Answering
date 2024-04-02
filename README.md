# Hallucination-Detection-in-Contextual-Question-Answering
This is project aimed at detecting hallucinations in contextual question answering LLM's.
# Overview
This project focuses on developing a system for detecting hallucinations in contextual question answering (CQA) systems. 
What are Hallucinations?
Hallucinations occur when a model generates answers that are not supported by the context provided. Detecting and addressing hallucinations is crucial for improving the reliability and trustworthiness of CQA systems.

# Motivation
The increasing use of CQA systems in various applications highlights the importance of ensuring the accuracy and credibility of generated answers. Hallucinations can lead to misinformation and reduce the overall performance of these systems. By detecting and mitigating hallucinations, we aim to enhance the quality of answers provided by CQA models.

# Approach
Our project employs state-of-the-art natural language processing techniques to identify hallucinations in CQA systems. We leverage contextual information, answer relevance, and consistency checks to flag potential hallucinations. By combining multiple signals and heuristics, our approach aims to accurately detect instances of hallucination in the generated answers. In this project we have used HHEM model from vectara through Hugging Face.

# Behind the model
The HHEM model is an open source model, created by Vectara, for detecting hallucinations in LLMs. It is particularly useful in the context of building retrieval-augmented-generation (RAG) applications where a set of facts is summarized by an LLM, but the model can also be used in other contexts.
This model was trained using SentenceTransformers Cross-Encoder class. The model outputs a probabilitity from 0 to 1, 0 being a hallucination and 1 being factually consistent. 


# Results
Our preliminary results demonstrate the effectiveness of our approach in detecting hallucinations in CQA systems. We report metrics such as precision, recall, and F1 score to evaluate the performance of our detection model. We have also built the AUC-ROC curve. Through thorough experimentation and analysis, we aim to continuously improve the accuracy and reliability of our system.

# Future Work
In the future, we plan to explore advanced deep learning architectures, incorporate external knowledge sources, and enhance the interpretability of our hallucination detection system. Additionally, we aim to collaborate with researchers and industry partners to deploy our solution in real-world CQA applications.

# Contributions
We welcome contributions, feedback, and collaborations from the research community and industry experts interested in improving the robustness and trustworthiness of contextual question answering systems. Together, we can advance the field of hallucination detection and enhance the overall quality of AI-driven question answering technologies.

# References:
https://huggingface.co/vectara/hallucination_evaluation_model
