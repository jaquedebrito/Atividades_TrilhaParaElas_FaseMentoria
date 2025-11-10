# Resumo do Projeto - Análise Exploratória de Dados

## 📊 Visão Geral

Este projeto apresenta uma análise exploratória completa do dataset B2W Reviews, focando em avaliações de produtos com visualizações e insights sobre comportamento do consumidor.

## 🎯 Objetivos

- Explorar padrões de avaliação por gênero e faixa etária
- Identificar categorias de produtos mais avaliadas
- Analisar correlação entre notas e recomendações
- Visualizar sentimentos através de nuvens de palavras

## 📈 Principais Descobertas

### Distribuição por Gênero
- Análise da proporção de avaliações entre diferentes gêneros
- Visualizações em gráficos de barras e pizza

### Categorias de Produtos
- Top 10 categorias mais avaliadas identificadas
- Produtos específicos com maior e menor número de avaliações
- Distribuição proporcional de avaliações por categoria

### Análise por Faixa Etária
- Segmentação: <20, 21-30, 31-40, 41-50, 51-60, 60+ anos
- Distribuição de avaliações por grupo etário
- Nuvens de palavras específicas para cada faixa

### Sentimento das Avaliações
- Análise de avaliações positivas (notas 4 e 5)
- Wordclouds revelando termos mais frequentes
- Correlação entre nota e recomendação do produto

## 🛠️ Tecnologias Utilizadas

- **Python 3.x** - Linguagem principal
- **Pandas** - Manipulação e análise de dados
- **Matplotlib** - Visualizações gráficas
- **WordCloud** - Geração de nuvens de palavras
- **HuggingFace Datasets** - Acesso ao dataset B2W Reviews

## 📊 Tipos de Visualizações

1. **Gráficos de Barras** - Distribuições e comparações
2. **Gráficos de Pizza** - Proporções e percentuais
3. **Nuvens de Palavras** - Análise textual e frequência de termos
4. **Tabelas Cruzadas** - Relações entre variáveis categóricas

## 🎓 Contexto Educacional

**Programa:** Trilha de IA para Elas  
**Fase:** Mentoria 2  
**Foco:** Análise Exploratória de Dados  
**Plataforma:** Google Colab

## 📦 Dataset

**Fonte:** [ruanchaves/b2w-reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01)  
**Conteúdo:** Avaliações de produtos de e-commerce brasileiro  
**Campos principais:** 
- Nota da avaliação (overall_rating)
- Gênero do avaliador
- Faixa etária
- Categoria do produto
- Texto da avaliação
- Recomendação (sim/não)

## 💡 Metodologia

1. **Carregamento de Dados** - Importação do dataset via HuggingFace
2. **Limpeza e Preparação** - Tratamento de valores ausentes e categorização
3. **Análise Exploratória** - Estatísticas descritivas e distribuições
4. **Visualização** - Criação de gráficos informativos
5. **Insights** - Interpretação dos resultados

## 📝 Estrutura dos Notebooks

- **Copy_of_Atividades_TrilhaParaElas.ipynb** - Notebook principal com todas as atividades
- **Copy_of_Encontro_1_TrilhaParaElasIA.ipynb** - Material do primeiro encontro
- **Copy_of_Encontro_2_TrilhaParaElasIA.ipynb** - Material do segundo encontro

## 🚀 Como Reproduzir

1. Instale as dependências: `pip install -r requirements.txt`
2. Abra o notebook no Google Colab ou Jupyter
3. Execute as células sequencialmente
4. Explore os resultados e visualizações

---

**Autora:** Jaqueline Brito  
**Data:** Junho/2025
