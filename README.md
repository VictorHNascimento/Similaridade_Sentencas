# 🔎 Similaridade de Reviews com NLP

## 📌 Sobre o Projeto

Este projeto tem como objetivo identificar **reviews mais similares** a partir de um tema ou texto fornecido pelo usuário, utilizando técnicas de **Processamento de Linguagem Natural (NLP)**.

Durante o desenvolvimento, exploramos diferentes abordagens para medir similaridade textual, evoluindo desde métodos baseados em palavras até modelos mais avançados baseados em embeddings de sentenças.

Ao final, foi construída uma aplicação interativa utilizando **Gradio**, permitindo que qualquer usuário insira um texto e receba como retorno as reviews mais semelhantes.

---

## 🎯 Objetivos do Projeto

- Identificar similaridade entre textos de forma eficiente  
- Explorar diferentes técnicas de vetorização textual  
- Comparar abordagens baseadas em palavras e sentenças  
- Aplicar modelos pré-treinados para melhorar os resultados  
- Disponibilizar o modelo em uma aplicação web acessível  

---

## 🧠 Abordagens Utilizadas

### 🔹 Word2Vec
- Representação de palavras em vetores numéricos
- Captura relações semânticas entre palavras
- Utilizado para medir similaridade em nível de vocabulário

---

### 🔹 Doc2Vec
- Extensão do Word2Vec para documentos completos
- Permite comparar textos maiores
- Utilizado para similaridade entre reviews completas

---

### 🔹 Universal Sentence Encoder (USE)
- Modelo pré-treinado desenvolvido pelo Google
- Gera embeddings de sentenças mais robustos
- Melhor desempenho na captura de contexto e significado

Com o **USE**, foi possível obter resultados mais consistentes na identificação de similaridade entre textos.

---

## 🚀 Aplicação

O projeto foi finalizado com o desenvolvimento de uma aplicação utilizando **Gradio**, onde é possível:

- Inserir um texto ou tema
- Comparar com um conjunto de reviews
- Retornar as mais semelhantes com base na similaridade semântica

Essa abordagem torna o modelo acessível mesmo para usuários sem conhecimento técnico.

---

## 🛠️ Tecnologias Utilizadas

- Python  
- TensorFlow Hub (Universal Sentence Encoder)  
- NumPy / Pandas  
- Gradio  

---

## 📊 Aprendizados

- Diferença entre similaridade de palavras e de sentenças  
- Uso de embeddings para NLP  
- Aplicação de modelos pré-treinados  
- Construção de aplicações interativas com Gradio  
- Pipeline completo de um projeto de NLP 
