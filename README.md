noorAI: An AI-Powered Exploration of Numerical and Linguistic Patterns in the Quran
Project Status: Phase 1 (Data Processing, Model Validation & Initial Analysis) - In Progress

1. Project Objective
noorAI is a self-directed R&D project designed to analyze the text of the Quran through a unique, dual-layered approach. The primary goal is to build an end-to-end data pipeline that transforms the sacred text into a structured, multi-dimensional dataset. This dataset is then used to explore potential numerical and linguistic patterns using a combination of traditional numerology (Abjad system), unsupervised machine learning, and advanced Natural Language Processing (NLP).

This initiative serves as a practical application of modern AI techniques to a classical, unstructured text, demonstrating a full-cycle approach from data engineering to model validation and analysis.

2. Core Features & Capabilities
The project is structured into a dual-level analysis pipeline:

Verse-Level Analysis
Numerical Fingerprinting: Each of the 6,000+ verses is assigned a rich numerical fingerprint based on statistical properties derived from the Abjad values of its words (e.g., total value, mean, standard deviation).

Unsupervised Clustering: A K-Means machine learning model is used to cluster verses based on their numerical similarities, revealing non-obvious groupings and patterns.

Semantic Search: A powerful NLP engine using Transformer models allows for natural language queries to find semantically related verses, regardless of exact keywords.

Word-Level Analysis
Linguistic Root Analysis (Lemmatization): Every word in the Quran (~77,000) is processed to identify its linguistic root, enabling powerful frequency and pattern analysis that transcends simple string matching.

Advanced Mathematical Analysis: The system can scan for complex numerical relationships between both Abjad values and word root frequencies (e.g., sums, multiples, and ratios matching mathematical constants).

"Grand Number String" Analysis: A novel approach where the Abjad values of all words are concatenated into a single string, which is then scanned for significant numerical sequences.

3. Technology Stack
This project was built entirely using open-source tools and libraries within a cloud-based environment.

Environment: Google Colab

Core Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn (K-Means Clustering, StandardScaler)

Natural Language Processing (NLP):

Semantic Search: Sentence-Transformers (based on Hugging Face)

Morphological Analysis: CAMeL Tools

Text Processing: PyArabic

Data Visualization: Plotly, Matplotlib, Seaborn

4. How to Use This Repository
The Python code for the full data processing pipeline and all analysis functions will be uploaded here as a series of Jupyter Notebooks (.ipynb). The final, processed datasets (in .parquet format) will also be made available for download.

This project is undertaken for the purpose of technical research and data science exploration. The findings are based on mathematical and linguistic analysis of a specific dataset and are presented as part of an ongoing R&D initiative.
