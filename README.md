# 📝 Film Junky Union Sentiment Analysis System

## Project Overview
Advanced sentiment analysis system for movie reviews, implementing from classical NLP techniques to state-of-the-art transformer models (BERT) for automatic polarity classification.

## Business Context
Film Junky Union needed to automate the analysis of thousands of user reviews to monitor movie reception, identify opinion trends, and optimize content strategies.

## Methodology & Approach
- **Advanced Preprocessing**: Complete pipeline with NLTK, spaCy, and regex
- **Feature Extraction**: TF-IDF vectorization and BERT embeddings
- **Comparative Modeling**: 5 approaches from classical to state-of-the-art
- **Deep Learning**: BERT implementation with PyTorch
- **Systematic Evaluation**: Accuracy, F1-score with custom function

## Technologies Used
- **Classical NLP**: NLTK (tokenization, stopwords, lemmatization)
- **Advanced NLP**: spaCy, TF-IDF Vectorizer
- **Deep Learning**: PyTorch, Transformers, BERT
- **Traditional ML**: Scikit-learn, LightGBM
- **Optimization**: TQDM for progress tracking

## Models Implemented
1. **Baseline**: Dummy Classifier
2. **Classical**: NLTK + TF-IDF + Logistic Regression
3. **Advanced**: spaCy + TF-IDF + Logistic Regression
4. **Ensemble**: spaCy + TF-IDF + LightGBM
5. **State-of-Art**: BERT + Custom Classification Layer

## Results & Business Value
- Modular pipeline with reusable functions
- Comprehensive comparison of NLP approaches
- Production-ready BERT implementation
- Framework applicable to social media and e-commerce analysis

## Technological Impact
- 80%+ automation of manual text analysis
- Scalability for processing millions of reviews
- Transferability to multiple domains (retail, social media, customer service)
