# Customer Intelligence & Sentiment Analysis Pipeline
Overview
This repository contains an end-to-end Natural Language Processing (NLP) and Machine Learning pipeline designed to extract actionable business intelligence from unstructured customer reviews. Using a dataset of over 10,000 Yelp reviews (restaurant_reviews_az.csv), this project explores the evolution of text analysis—from foundational linguistic processing to deep learning and generative AI architectures.

Project Architecture & Repository Structure
The repository is structured sequentially to demonstrate the progression from raw text processing to advanced Large Language Model (LLM) classification.

1. NLP Foundations
01_nlp_text_processing_foundations.ipynb

Implements foundational linguistic processing including tokenization, POS tagging, Lemmatization, and Named Entity Recognition (NER) utilizing Spacy and NLTK to uncover baseline linguistic patterns in customer satisfaction.

2. Predictive Machine Learning
02_supervised_ml_sentiment_classification.ipynb

Benchmarks traditional supervised learning models (Naive Bayes, SVM, Logistic Regression) against VADER lexicon approaches.

Quantifies text using Bag of Words (CountVectorizer) and TF-IDF to predict sentiment classifications.

3. Advanced Topic Modeling & Temporal Trends
03_bertopic_umap_topic_modeling.ipynb

Extracts hidden themes and customer pain points using BERTopic.

Implements UMAP for dimensionality reduction to visualize trending topic frequencies and business insights over a two-year period.

4. Deep Learning Classification
04_deep_learning_rnn_lstm_classification.ipynb

Classifies complex sentiment utilizing advanced Neural Networks.

Architects, trains, and compares Artificial Neural Networks (ANN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) networks via TensorFlow/Keras using 5000-dimensional TF-IDF and word embeddings.

5. Generative AI & Prompt Engineering
05_llm_zero_shot_few_shot_prompting.ipynb

Benchmarks the performance of local Large Language Models (Llama 3.2, Mistral) deployed via Ollama.

Evaluates precision, recall, and accuracy using both zero-shot and few-shot prompt engineering techniques to classify nuanced customer feedback.

Tech Stack
Languages & Libraries: Python, Pandas, Scikit-learn, Spacy, NLTK

Deep Learning: TensorFlow, Keras

LLMOps & GenAI: Ollama, Llama 3.2, Mistral, Prompt Engineering

Topic Modeling: BERTopic, UMAP

Business Impact
This pipeline successfully translates raw, unstructured text into temporal business insights. By benchmarking everything from traditional machine learning to advanced generative AI models, it provides a data-driven framework for determining the most cost-effective and accurate tech stack for analyzing customer experience at scale.
