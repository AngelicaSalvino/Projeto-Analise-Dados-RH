# Análise de Dados de RH

Este repositório contém o script de um Jupyter Notebook com uma análise completa de dados de Recursos Humanos (RH). O objetivo do projeto é compreender e diagnosticar dados de candidatos a Cientistas de Dados, identificando padrões, correlações e insights que possam apoiar o processo de contratação da empresa de consultoria em Big Data e Data Science.

## Fonte de Dados

Os dados utilizados neste projeto foram obtidos do seguinte link no Kaggle:  [HR Analytics: Job Change of Data Scientists.](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists). Este conjunto de dados foi desenvolvido para entender os fatores que levam uma pessoa a deixar o emprego atual, sendo aplicável para pesquisas de RH.

## Ferramentas Utilizadas

* **Manipulação de Dados:**
* Pandas
* Numpy

* **Visualização:**
* Matplotlib
* Seaborn
* Plotly

* **Estatística:**
* Scipy

* **Engenharia de Atributos:**
* Scikit-learn
* Category Encoders

* **Ignorar Avisos:**
* Warnings

## Carregamento dos Dados

Os dados foram carregados a partir do arquivo CSV `aug_train.csv` usando a biblioteca Pandas. O conjunto de dados possui 19.158 entradas e 14 colunas.

## Análise Exploratória de Dados

* Descrição estatística de variáveis categóricas e numéricas.
* Visualização de variáveis categóricas por meio de gráficos de contagem.
* Verificação da distribuição de variáveis numéricas com histogramas e boxplots.
* Teste de normalidade da distribuição para algumas variáveis numéricas.

## Correlação dos Dados

* Correlação de Spearman entre variáveis numéricas, visualizada por meio de um heatmap.

## Weight of Evidence (WOE) e Information Value (IV)
* Cálculo do WOE e IV para variáveis categóricas, proporcionando insights sobre a importância preditiva de cada variável em relação à variável alvo.

## Tratamento de Valores Ausentes

* Identificação e imputação de valores ausentes em variáveis específicas, considerando a lógica do domínio.
* Ajustes Finais
* Pequenos ajustes nos dados, como renomear categorias e remover variáveis menos relevantes.

## Recomendações
Com base na análise, recomenda-se que o RH da empresa:
1. Priorize candidatos de cidades com índice de desenvolvimento urbano mais baixo: Isso pode ser uma estratégia eficaz para encontrar candidatos que estão procurando ativamente emprego.

2. Considere candidatos sem experiência relevante: Muitos candidatos sem experiência relevante podem estar dispostos a aprender e crescer na empresa.

3. Ofereça treinamento mais compacto: Dado que a maioria dos candidatos não precisa de muito tempo para concluir o treinamento, a empresa pode otimizar o processo de treinamento.

4. Explore outras fontes de dados: O RH pode desenvolver métodos adicionais para coletar dados relevantes que possam melhorar a precisão da análise.

Este README fornece uma visão geral do projeto e das principais conclusões. Para obter detalhes completos, consulte o Jupyter Notebook.
