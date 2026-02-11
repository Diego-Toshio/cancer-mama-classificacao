# Comparação de Modelos de Regressão Logística para Diagnóstico de Câncer de Mama

## 📌 Contexto
O diagnóstico precoce do câncer de mama é um fator determinante para o aumento
das chances de tratamento eficaz. Modelos de Machine Learning podem atuar como
ferramentas auxiliares na análise de dados clínicos, apoiando a tomada de decisão
com base em padrões identificados nos dados.

Este projeto explora o uso da Regressão Logística para classificação de diagnósticos
em benignos e malignos.

## 🎯 Objetivo
Desenvolver e comparar dois modelos de Regressão Logística:

- **Modelo Baseline:** utilizando apenas as duas variáveis mais correlacionadas com o diagnóstico;
- **Modelo Completo:** utilizando um conjunto mais amplo de atributos disponíveis.

O objetivo é avaliar o impacto da seleção de features no desempenho preditivo
e na capacidade de generalização do modelo.

## 📊 Dataset
O dataset utilizado é o **Breast Cancer Wisconsin (Diagnostic)**,
disponibilizado pela biblioteca Scikit-learn.

Ele contém 30 variáveis numéricas extraídas de imagens digitalizadas de
biópsias de mama, relacionadas a características de forma e textura celular.

A variável-alvo classifica os diagnósticos como:
- Benigno
- Maligno

Este dataset é amplamente utilizado como benchmark em problemas de
classificação médica.

## 🧠 Abordagem
- Análise Exploratória Inicial
- Seleção das variáveis mais correlacionadas
- Padronização das features (StandardScaler)
- Treinamento dos modelos de Regressão Logística
- Avaliação com métricas de classificação


## 📈 Resultados
Os resultados indicaram desempenho elevado para ambos os modelos,
com melhora observada ao utilizar o conjunto completo de features.


## 🛠️ Tecnologias
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Estrutura do Repositório
cancer-mama-classificacao/
- CancerDeMama_Regressao_Logistica.ipynb
- README.md

## 📌 Observações
Este projeto demonstra a aplicação estruturada de um modelo de classificação
em um contexto médico, destacando a importância da seleção de variáveis
para garantir robustez e generalização.
