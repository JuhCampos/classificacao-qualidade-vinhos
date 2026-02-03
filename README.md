# Classificação de Qualidade de Vinhos Tintos

Este projeto aplica técnicas de Ciência de Dados e Machine Learning para classificar a qualidade de vinhos tintos com base em suas propriedades físico-químicas. 
O objetivo é identificar quais fatores influenciam uma nota de qualidade superior e construir um modelo preditivo.

## O Dataset
Os dados foram obtidos do Kaggle. O conjunto de dados contém informações de vinhos tintos "vinho verde" do norte de Portugal.

### Variáveis analisadas:
* Acidez (fixa, volátil, cítrica), Açúcar residual, Cloretos, Dióxido de enxofre, Densidade, pH, Sulfatos e Teor Alcoólico.

## Tecnologias e Bibliotecas
* **Python** (Linguagem base)
* **Pandas & NumPy**: Manipulação e tratamento de dados.
* **Matplotlib & Seaborn**: Visualização de dados e matrizes de correlação.
* **Scikit-Learn**: Divisão de treino/teste e implementação do modelo.

## Metodologia e Insights
Durante o desenvolvimento, segui as seguintes etapas presentes no notebook:

1. **Análise Exploratória (EDA):** Identifiquei que o **Teor Alcoólico (alcohol)** possui a correlação positiva mais forte com a qualidade do vinho.
2. **Pré-processamento:** Limpeza de dados e separação entre variáveis explicativas (X) e o alvo (y).
3. **Modelagem:** Árvore de Decisão com ajuste de hiperparâmetros (max_depth e ccp_alpha) para evitar overfitting e garantir a generalização do modelo, validada via Curvas de Aprendizado.
