# 📝 Film Junky Union Sentiment Analysis System

## Descripción del Proyecto
Sistema avanzado de análisis de sentimientos para reseñas cinematográficas, implementando desde técnicas clásicas de NLP hasta modelos transformer de última generación (BERT) para clasificación automática de polaridad.

## Contexto de Negocio
Film Junky Union necesitaba automatizar el análisis de miles de reseñas de usuarios para monitorear la recepción de películas, identificar tendencias de opinión y optimizar estrategias de contenido.

## Metodología y Enfoque
- **Preprocessing avanzado**: Pipeline completo con NLTK, spaCy y regex
- **Feature Extraction**: TF-IDF vectorization y BERT embeddings
- **Modelado comparativo**: 5 enfoques desde clásico hasta estado del arte
- **Deep Learning**: Implementación de BERT con PyTorch
- **Evaluación sistemática**: Accuracy, F1-score con función personalizada

## Tecnologías Utilizadas
- **NLP Classical**: NLTK (tokenización, stopwords, lemmatización)
- **NLP Advanced**: spaCy, TF-IDF Vectorizer
- **Deep Learning**: PyTorch, Transformers, BERT
- **ML Traditional**: Scikit-learn, LightGBM
- **Optimization**: TQDM para progress tracking

## Modelos Implementados
1. **Baseline**: Dummy Classifier
2. **Classical**: NLTK + TF-IDF + Logistic Regression
3. **Advanced**: spaCy + TF-IDF + Logistic Regression
4. **Ensemble**: spaCy + TF-IDF + LightGBM
5. **State-of-Art**: BERT + Custom Classification Layer

## Resultados y Valor Empresarial
- Pipeline modular con funciones reutilizables
- Comparación exhaustiva de enfoques NLP
- Implementación production-ready de BERT
- Framework aplicable a análisis de redes sociales y e-commerce

## Impacto Tecnológico
- Automatización del 80%+ del análisis manual de texto
- Escalabilidad para procesamiento de millones de reseñas
- Transferibilidad a múltiples dominios (retail, social media, customer service)
