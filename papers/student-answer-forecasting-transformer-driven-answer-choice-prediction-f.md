# Student Answer Forecasting: Transformer-Driven Answer Choice Prediction for Language Learning

Elena Grazia Gado, Tommaso Martorella, Luca Zunino, Paola Mejia-Domenzain, Vinitra Swamy, Jibril Frej, Tanja Käser
2024 · arXiv preprint

## Abstract

Intelligent Tutoring Systems (ITS) enhance personalized learning by predicting student answers to provide immediate and customized instruction. However, recent research has primarily focused on the correctness of the answer rather than the student's performance on specific answer choices, limiting insights into students' thought processes and potential misconceptions. To address this gap, we present MCQStudentBert, an answer forecasting model that leverages the capabilities of Large Language Models (LLMs) to integrate contextual understanding of students' answering history along with the text of the questions and answers. By predicting the specific answer choices students are likely to make, practitioners can easily extend the model to new answer choices or remove answer choices for the same multiple-choice question (MCQ) without retraining the model. In particular, we compare MLP, LSTM, BERT, and Mistral 7B architectures to generate embeddings from students' past interactions, which are then incorporated into a finetuned BERT's answer-forecasting mechanism. We apply our pipeline to a dataset of language learning MCQ, gathered from an ITS with over 10,000 students to explore the predictive accuracy of MCQStudentBert, which incorporates student interaction patterns, in comparison to correct answer prediction and traditional mastery-learning feature-based approaches. This work opens the door to more personalized content, modularization, and granular support.

## Links
- DOI: https://doi.org/10.48550/arxiv.2405.20079
- arXiv: https://doi.org/10.48550/arxiv.2405.20079
- PDF: https://arxiv.org/pdf/2405.20079
- Licence: CC-BY
- HTML: https://paola-md.github.io/papers/student-answer-forecasting-transformer-driven-answer-choice-prediction-f.html
- Cite: https://paola-md.github.io/publications.bib

Part of the publication record of Paola Mejia-Domenzain — https://paola-md.github.io/
