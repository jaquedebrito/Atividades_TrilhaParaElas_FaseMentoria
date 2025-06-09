# Atividades de Análise Exploratória de Dados - Trilha de IA para Elas

Este repositório contém as atividades desenvolvidas a partir da aula referente à **Mentoria 2** da Trilha de IA para Elas, utilizando o dataset de avaliações de produtos (B2W Reviews) disponível no HuggingFace.

O projeto foi originalmente desenvolvido em Google Colab, com base no notebook:  
[Copy of Atividades_TrilhaParaElas.ipynb](https://colab.research.google.com/drive/1q-bFzPaZM-O8_r1lK2dZYQzlyYoE4pEB?usp=sharing)

## Atividades Desenvolvidas

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

## Tecnologias utilizadas

- [Google Colab](https://colab.research.google.com/)
- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [WordCloud](https://github.com/amueller/word_cloud)
- [Datasets (HuggingFace)](https://huggingface.co/docs/datasets/)

## Como utilizar

1. Clone este repositório ou faça o download do notebook/script.
2. Execute no Google Colab ou em seu ambiente Python local.
3. Instale as dependências necessárias (disponíveis nas primeiras células do notebook).

## Dataset

O dataset utilizado é o [ruanchaves/b2w-reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01), disponível no HuggingFace Datasets.

---

**Trilha de IA para Elas**  
Mentoria 2 — Análise Exploratória de Dados

**Autora:** Jaqueline Brito  
**Data:** 09/06/2025  
