[![author](https://img.shields.io/badge/author-dani-blue.svg)](https://www.linkedin.com/in/daniele-santiago/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-blue.svg?style=flat)](https://github.com/danielesantiago/Data-Science)

<p align="center">
  <img src="https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Arquivos/ds.png?raw=true" >
</p>

# Portfólio de Ciência de Dados
Este repositório armazena as análises desenvolvidas durante o curso "Data Science na Prática" da Sigmoidal, bem como aprendizados próprios.
_Nota: Os dados utilizados nos projetos (acessados no diretório de dados) são apenas para fins de demonstração._

## Instruções para Execução dos Notebooks em Python Localmente
1. Instale as dependências necessárias.
2. Execute os notebooks como de costume, usando um servidor Jupyter Notebook, Vscode, etc.

## Tópicos

- ### Análise Exploratória

	- [Análise dos Dados do Airbnb em Hong Kong](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/An%C3%A1lise%20dos%20Dados%20do%20Airbnb%20-%20Hong%20Kong.ipynb): Uma análise dos dados do Airbnb na cidade de Hong Kong, utilizando ferramentas de análise estatística para entender os preços médios, tipos de imóveis disponíveis e suas localizações. Além disso, o notebook apresenta visualizações e insights sobre as avaliações dos usuários e os requisitos mais buscados pelos hóspedes.
	- [Panorama da COVID-19](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Panorama%20da%20COVID-19.ipynb): Uma análise dos dados da COVID-19 em nível mundial, utilizando ferramentas de visualização para apresentar a evolução dos casos confirmados, mortes e taxas de recuperação em diferentes países. Além disso, o notebook apresenta uma análise dos dados em relação à densidade populacional e IDH dos países, buscando entender possíveis fatores que influenciam a disseminação da doença.

	_Ferramentas: Pandas, Seaborn, Matplotlib_

- ### Machine Learning

	- [Detecção de Fraudes em Cartões de Crédito](https://bit.ly/3Fn7zv4): Neste projeto, é utilizada uma base de dados de transações de cartões de crédito para desenvolver um modelo de aprendizado de máquina capaz de identificar fraudes. São utilizadas técnicas de pré-processamento, análise exploratória e seleção de atributos para treinar modelos de classificação, buscando maximizar a identificação de transações fraudulentas e minimizar falsos positivos.
	- [Churn Prediction](https://bit.ly/3L0Rb6I): Neste projeto, é desenvolvido um modelo de aprendizado de máquina para prever a taxa de churn de clientes em uma empresa fictícia. São utilizadas técnicas de pré-processamento, análise exploratória e seleção de atributos para treinar modelos de classificação, buscando prever quais clientes têm maior probabilidade de abandonar a empresa e identificar possíveis fatores que influenciam nessa decisão. O objetivo final é ajudar a empresa a tomar medidas preventivas para reduzir a taxa de churn e aumentar a retenção de clientes.
	- [Credit Risk Analysis](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Credit%20Risk%20Analysis.ipynb): Neste projeto, é utilizada uma base de dados financeiros de clientes para desenvolver um modelo de aprendizado de máquina capaz de avaliar o risco de crédito. O objetivo é prever a probabilidade de um cliente não cumprir com suas obrigações financeiras, o que é conhecido como default. São utilizadas técnicas de pré-processamento para preparar os dados para o treinamento do modelo. Isso pode envolver a limpeza dos dados, tratamento de valores ausentes, e a transformação de variáveis categóricas em numéricas, além de feature engineering, feature selection e balanceamento de classes


	_Ferramentas: Sklearn, Imblearn, Pandas, Seaborn, Matplotlib_
  
- ### Auto Machine Learning

	- [Classificação de Saúde Fetal](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Fetal%20Health%20Classification.ipynb): Neste projeto, é desenvolvido um modelo de classificação para prever a saúde fetal com base em dados clínicos. São utilizadas técnicas de pré-processamento e análise exploratória para entender a distribuição dos dados e identificar possíveis correlações entre as variáveis. Em seguida, diferentes modelos de aprendizado de máquina são treinados e avaliados para encontrar o que apresenta o melhor desempenho na classificação das diferentes condições de saúde fetal.

	- [Previsão de Custos de Seguro de Saúde](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Health%20Insurance%20Cost%20Prediction.ipynb): Neste projeto, é desenvolvido um modelo de regressão para prever os custos de seguro de saúde com base em informações sobre os segurados. São utilizadas técnicas de pré-processamento e análise exploratória para entender a distribuição dos dados e identificar possíveis correlações entre as variáveis. Em seguida, diferentes modelos de regressão são treinados e avaliados para encontrar o que apresenta o melhor desempenho na previsão dos custos de seguro de saúde. O objetivo final é ajudar as seguradoras a estimar os custos de seus segurados e definir preços mais justos para seus planos de saúde.

	_Ferramentas: Pycaret, Sklearn, Imblearn, Pandas, Seaborn, Matplotlib_
	
- ### Deep Learning

	- [Classificador de Fake News](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Classificador%20de%20Fake%20News.ipynb): Neste projeto, desenvolvemos um modelo de classificação de notícias como verdadeiras ou falsas, por meio de redes neurais. O objetivo é criar um classificador de aprendizado de máquina capaz de detectar automaticamente notícias falsas, auxiliando no combate à desinformação. Utilizando um conjunto de treinamento de notícias rotuladas, o modelo é treinado para identificar padrões e distinguir entre notícias verdadeiras e falsas. Esse projeto contribui para a identificação e mitigação da propagação de informações enganosas, visando a promoção de um ambiente informacional mais confiável e seguro.
	
	_Ferramentas: Tensorflow, Sklearn, Pandas, Numpy, Seaborn, Matplotlib_
  
- ### Séries Temporais

	- [Previsão de Demanda de Vinhos com Séries Temporais](https://github.com/danielesantiago/Data-Science/blob/main/An%C3%A1lises/Previs%C3%A3o%20de%20Demanda%20de%20Vinhos%20com%20S%C3%A9ries%20Temporais.ipynb): : Neste projeto, é desenvolvido um modelo de previsão de demanda de vinhos com base em séries temporais. São utilizados dados históricos de vendas para treinar e testar diferentes modelos de previsão, como ARIMA, Prophet e LSTM. São utilizadas técnicas de pré-processamento e análise exploratória para entender a distribuição dos dados e identificar possíveis tendências e sazonalidades. O objetivo final é ajudar uma vinícola a antecipar a demanda por seus produtos e otimizar sua produção e distribuição.
  
	_Ferramentas: Prophet, Sklearn, Pandas, Seaborn, Matplotlib_
  
