# Information Retrieval Coursework Project

## Overview
This project for the Information Retrieval course delves into the development and comparison of various retrieval algorithms. Using a TREC dataset annotated for the task, we focused on understanding and implementing key algorithms in the field, demonstrating their efficiency and effectiveness in retrieving relevant information.

## Key Features

### Implemented Algorithms
1. **Boolean Retrieval:**
   - Implemented the fundamental Boolean retrieval model, allowing for exact matching of queries with documents using logical operators.

2. **Similarity-Based Retrieval:**
   - Developed algorithms that rank documents based on their similarity to a query, providing more nuanced and relevant results compared to Boolean retrieval.

3. **TF-IDF (Term Frequency-Inverse Document Frequency):**
   - Utilized the TF-IDF model to evaluate how important a word is to a document in a collection, aiding in the identification of relevant documents.

### Pseudo-Relevance Feedback
- Incorporated pseudo-relevance feedback mechanisms to refine search results. This approach assumes that top-ranked search results in an initial query are relevant and uses this information to improve the search accuracy in subsequent iterations.

### Efficient Information Retrieval Techniques
- Explored and implemented various techniques to improve the efficiency and effectiveness of information retrieval, focusing on the optimization of search algorithms and query processing.

### BM25 for Ranking
- Used the BM25 algorithm, a more advanced approach compared to traditional TF-IDF, for ranking documents. BM25 provides better handling of term frequency saturation and document length normalization.

### Dataset and Practical Application
- The project utilized the PSGRobust dataset, enabling hands-on experience with real-world data.
- Emphasis was placed on practical application, comparing different retrieval methods and understanding their strengths and limitations in various scenarios.

### Educational Objective
- The primary goal was to gain a comprehensive understanding of different information retrieval algorithms and their applications.
- The coursework facilitated a deeper insight into the mechanics and theoretical underpinnings of IR systems.

## Citation
This project was heavily influenced by the work of Keping Bi, Qingyao Ai, and W. Bruce Croft in their paper:

- Keping Bi, Qingyao Ai, W. Bruce Croft. "Iterative Relevance Feedback for Answer Passage Retrieval with Passage-level Semantic Match." Proceedings of the European Conference on Information Retrieval (ECIR 19), Cologne, Germany, April 14-18, 2019, pp. 558-572.

This seminal paper provided crucial insights and methodologies that shaped our understanding and implementation of information retrieval algorithms.

---

For more information or inquiries about the project, please contact the project team and any queries feel free to create a PR
