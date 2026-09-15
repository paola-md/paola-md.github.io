# Enhancing Procedural Writing Through Personalized Example Retrieval: A Case Study on Cooking Recipes

Paola Mejia-Domenzain, Jibril Frej, Seyed Parsa Neshaei, Luca Mouchel, Tanya Nazaretsky, Thiemo Wambsganß, Antoine Bosselut, Tanja Käser
2024 · International Journal of Artificial Intelligence in Education

**Finding.** Retrieving a worked example matched to the learner's own draft improved both writing performance and experience, drawing on a database of over 180,000 recipes.

## Abstract

Writing high-quality procedural texts is a challenging task for many learners. While example-based learning has shown promise as a feedback approach, a limitation arises when all learners receive the same content without considering their individual input or prior knowledge. Consequently, some learners struggle to grasp or relate to the feedback, finding it redundant and unhelpful. To address this issue, we present RELEX , an adaptive learning system designed to enhance procedural writing through personalized example-based learning. The core of our system is a multi-step example retrieval pipeline that selects a higher quality and contextually relevant example for each learner based on their unique input. We instantiate our system in the domain of cooking recipes. Specifically, we leverage a fine-tuned Large Language Model to predict the quality score of the learner’s cooking recipe. Using this score, we retrieve recipes with higher quality from a vast database of over 180,000 recipes. Next, we apply BM25 to select the semantically most similar recipe in real-time. Finally, we use domain knowledge and regular expressions to enrich the selected example recipe with personalized instructional explanations. We evaluate RELEX in a 2 x 2 controlled study (personalized vs. non-personalized examples, reflective prompts vs. none) with 200 participants. Our results show that providing tailored examples contributes to better writing performance and user experience.

## Links
- DOI: https://doi.org/10.1007/s40593-024-00405-1
- PDF: https://link.springer.com/content/pdf/10.1007/s40593-024-00405-1.pdf
- Licence: CC-BY
- HTML: https://paola-md.github.io/papers/enhancing-procedural-writing-through-personalized-example-retrieval-a-ca.html
- Cite: https://paola-md.github.io/publications.bib

Part of the publication record of Paola Mejia-Domenzain, https://paola-md.github.io/
