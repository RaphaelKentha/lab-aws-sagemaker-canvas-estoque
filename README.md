# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning.

## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

## 🚀 Passo a Passo

### 1. Selecionar Dataset

- dataset-1000-com-preco-promocional-e-renovacao-estoque.csv

### 2. Construir/Treinar

- Coluna-alvo => PRECO
- Tipo de modelo => previsão de séries temporais
- Objetivo: Analisar o impacto da variação de preços no estoque dos produtos

### 3. Analisar

- Avg.wQL=> 0.069
- WAPE => 0.111
- RMSE => 1.699
- MAPE => 0.121
- MASE => 0.881
- Impacto em QUANTIDADE_ESTOQUE => 46.19%

### 4. Prever

- Com base nos indicadores fornecidos (Avg.wQL: 0.069, MAPE: 0.121, WAPE: 0.111, RMSE: 1.699, MASE: 0.881, Impacto em QUANTIDADE_ESTOQUE: 46.19%), observa-se que, em média, todos os produtos apresentam uma redução significativa no estoque. Em alguns casos, o estoque pode diminuir até 50% do valor original. 
- Portanto, há uma correlação direta entre a redução de preço ao longo do tempo e o aumento na quantidade de itens comprados. É importante notar que esta análise não considera variações sazonais, como datas festivas, nem produtos que possam estar em alta demanda temporária.
