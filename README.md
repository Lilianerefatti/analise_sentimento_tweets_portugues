# analise_sentimento_tweets_portugues
Análise de Sentimento de Tweets em Português

Este projeto realiza a análise de sentimentos de tweets usando técnicas de NLP (Processamento de Linguagem Natural) e algoritmos de classificação de Machine Learning.

## 🔍 Objetivo
- Limpar e traduzir os textos de tweets
- Gerar nuvens de palavras por sentimento
- Treinar e avaliar diferentes modelos (Naive Bayes, SVM, Random Forest e Regressão Logística)
- Exportar modelos prontos para uso futuro

## 🧠 Modelos Usados
- Naive Bayes
- SVM (Support Vector Machine)
- Random Forest
- Regressão Logística

## 📊 Avaliação
Todos os modelos apresentaram alta acurácia nos dados. Foi utilizado TF-IDF para vetorização, matriz de confusão e métricas como F1-score para avaliação.

## 📁 Organização
- `notebooks/`: Notebook com a análise completa
- `models/`: Modelos e vetorizadores exportados
- `images/`: Wordclouds e gráficos de avaliação
- `data/`: Dataset original (se permitido pela licença)

## ✅ Tecnologias
- Python, Pandas, Scikit-Learn, NLTK, Seaborn, Matplotlib, WordCloud

---

🔗 Dataset: [Tweet Sentiment Classification Dataset - Kaggle](https://www.kaggle.com/datasets/sahideseker/tweet-sentiment-classification-dataset)
