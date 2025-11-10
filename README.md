# 📊 Atividades de Análise Exploratória de Dados - Trilha de IA para Elas

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[🇧🇷 Português](#português) | [🇺🇸 English](#english)

---

## 🇧🇷 Português

### Sobre o Projeto

Este repositório contém as atividades desenvolvidas a partir da aula referente à **Mentoria 2** da Trilha de IA para Elas, utilizando o dataset de avaliações de produtos (B2W Reviews) disponível no HuggingFace.

O projeto foi originalmente desenvolvido em Google Colab, com base no notebook:  
[Copy of Atividades_TrilhaParaElas.ipynb](https://colab.research.google.com/drive/1q-bFzPaZM-O8_r1lK2dZYQzlyYoE4pEB?usp=sharing)

### 📋 Atividades Desenvolvidas

As atividades exploram técnicas de análise exploratória de dados, visualização e manipulação de DataFrames com pandas, matplotlib e wordcloud, incluindo:

1. **Distribuição do número de avaliações por gênero**  
   - Gráfico de barras representando o número de avaliações por gênero.
2. **Proporção do número de avaliações por gênero**  
   - Gráfico de pizza mostrando a proporção de avaliações por gênero.
3. **Top 10 categorias de produtos mais avaliadas**  
   - Gráfico de barras das 10 categorias de produtos mais avaliadas.
4. **Top 5 produtos mais e menos avaliados**  
   - Identificação dos produtos mais e menos avaliados.
5. **Proporção de avaliação das top 10 categorias de produtos**  
   - Gráfico de pizza com a proporção de avaliações das 10 categorias mais avaliadas.
6. **Proporção de avaliação entre avaliadores de 31–40 anos**  
   - Gráfico de pizza para analisar avaliações entre 31 e 40 anos.
7. **Nuvem de palavras das avaliações positivas**  
   - Geração de uma wordcloud com palavras mais frequentes nos textos de avaliações positivas (notas 4 e 5).
8. **Nuvem de palavras por faixa etária**  
   - Criação de nuvens de palavras para cada faixa etária, considerando o título das avaliações.
9. **Gráfico de barras da distribuição de avaliações por faixa etária**  
   - Análise da quantidade de avaliações por faixa etária definida em: `<20`, `21–30`, `31–40`, `41–50`, `51–60`, `60+`.
10. **Tabela cruzada (crosstab) entre avaliação e recomendação**  
    - Tabela cruzada demonstrando a relação entre a nota da avaliação (`overall_rating`) e se o usuário recomendaria o produto para um amigo (`recommend_to_a_friend`).

### 🛠️ Tecnologias Utilizadas

- [Google Colab](https://colab.research.google.com/)
- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [WordCloud](https://github.com/amueller/word_cloud)
- [Datasets (HuggingFace)](https://huggingface.co/docs/datasets/)

### 🚀 Como Utilizar

#### Pré-requisitos

- Python 3.x instalado
- Conta no Google Colab (opcional, para execução online)

#### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/jaquedebrito/Atividades_TrilhaParaElas_FaseMentoria.git
cd Atividades_TrilhaParaElas_FaseMentoria
```

2. Instale as dependências necessárias:
```bash
pip install -r requirements.txt
```

#### Execução

**Opção 1: Google Colab (Recomendado)**
1. Abra o link do notebook no Google Colab
2. Execute as células sequencialmente

**Opção 2: Ambiente Local**
1. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```
2. Abra o arquivo `Copy_of_Atividades_TrilhaParaElas.ipynb`
3. Execute as células sequencialmente

### 📊 Dataset

O dataset utilizado é o [ruanchaves/b2w-reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01), disponível no HuggingFace Datasets.

### 📁 Estrutura do Repositório

```
.
├── Copy_of_Atividades_TrilhaParaElas.ipynb       # Notebook principal
├── Copy_of_Encontro_1_TrilhaParaElasIA.ipynb     # Material do Encontro 1
├── Copy_of_Encontro_2_TrilhaParaElasIA.ipynb     # Material do Encontro 2
├── requirements.txt                               # Dependências do projeto
├── SUMMARY.md                                     # Resumo executivo do projeto
└── README.md                                      # Este arquivo
```

### 📚 Documentação Adicional

- **[SUMMARY.md](SUMMARY.md)** - Resumo executivo com principais descobertas e insights do projeto

### 👩‍💻 Autora

**Jaqueline Brito**  
[GitHub](https://github.com/jaquedebrito)

### 📅 Informações do Projeto

- **Programa:** Trilha de IA para Elas
- **Fase:** Mentoria 2
- **Foco:** Análise Exploratória de Dados
- **Data:** Junho/2025

---

## 🇺🇸 English

### About the Project

This repository contains activities developed for **Mentorship 2** of the "Trilha de IA para Elas" (AI Path for Women) program, using the B2W Reviews product evaluation dataset available on HuggingFace.

The project was originally developed in Google Colab, based on the notebook:  
[Copy of Atividades_TrilhaParaElas.ipynb](https://colab.research.google.com/drive/1q-bFzPaZM-O8_r1lK2dZYQzlyYoE4pEB?usp=sharing)

### 📋 Activities Developed

The activities explore exploratory data analysis techniques, visualization, and DataFrame manipulation with pandas, matplotlib, and wordcloud, including:

1. **Distribution of reviews by gender**  
   - Bar chart representing the number of reviews by gender
2. **Proportion of reviews by gender**  
   - Pie chart showing the proportion of reviews by gender
3. **Top 10 most reviewed product categories**  
   - Bar chart of the 10 most reviewed product categories
4. **Top 5 most and least reviewed products**  
   - Identification of the most and least reviewed products
5. **Review proportion of top 10 product categories**  
   - Pie chart with the proportion of reviews of the 10 most reviewed categories
6. **Review proportion among reviewers aged 31-40**  
   - Pie chart to analyze reviews among 31-40 year olds
7. **Word cloud of positive reviews**  
   - Generation of a wordcloud with the most frequent words in positive review texts (ratings 4 and 5)
8. **Word clouds by age group**  
   - Creation of word clouds for each age group, considering review titles
9. **Bar chart of review distribution by age group**  
   - Analysis of the number of reviews by age group defined as: `<20`, `21-30`, `31-40`, `41-50`, `51-60`, `60+`
10. **Cross-tabulation between rating and recommendation**  
    - Cross table demonstrating the relationship between review rating (`overall_rating`) and whether the user would recommend the product to a friend (`recommend_to_a_friend`)

### 🛠️ Technologies Used

- [Google Colab](https://colab.research.google.com/)
- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [WordCloud](https://github.com/amueller/word_cloud)
- [Datasets (HuggingFace)](https://huggingface.co/docs/datasets/)

### 🚀 How to Use

#### Prerequisites

- Python 3.x installed
- Google Colab account (optional, for online execution)

#### Installation

1. Clone this repository:
```bash
git clone https://github.com/jaquedebrito/Atividades_TrilhaParaElas_FaseMentoria.git
cd Atividades_TrilhaParaElas_FaseMentoria
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

#### Execution

**Option 1: Google Colab (Recommended)**
1. Open the notebook link in Google Colab
2. Run cells sequentially

**Option 2: Local Environment**
1. Start Jupyter Notebook:
```bash
jupyter notebook
```
2. Open the file `Copy_of_Atividades_TrilhaParaElas.ipynb`
3. Run cells sequentially

### 📊 Dataset

The dataset used is [ruanchaves/b2w-reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01), available on HuggingFace Datasets.

### 📁 Repository Structure

```
.
├── Copy_of_Atividades_TrilhaParaElas.ipynb       # Main notebook
├── Copy_of_Encontro_1_TrilhaParaElasIA.ipynb     # Meeting 1 materials
├── Copy_of_Encontro_2_TrilhaParaElasIA.ipynb     # Meeting 2 materials
├── requirements.txt                               # Project dependencies
├── SUMMARY.md                                     # Executive summary
└── README.md                                      # This file
```

### 📚 Additional Documentation

- **[SUMMARY.md](SUMMARY.md)** - Executive summary with main findings and insights from the project

### 👩‍💻 Author

**Jaqueline Brito**  
[GitHub](https://github.com/jaquedebrito)

### 📅 Project Information

- **Program:** Trilha de IA para Elas (AI Path for Women)
- **Phase:** Mentorship 2
- **Focus:** Exploratory Data Analysis
- **Date:** June/2025

---

**Trilha de IA para Elas**  
Mentoria 2 — Análise Exploratória de Dados

**Autora:** Jaqueline Brito  
**Data:** 09/06/2025  
