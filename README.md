# Previsão de Texto para Anúncios do Airbnb com Data Science e Machine Learning

Este projeto tem como objetivo prever descrições textuais para anúncios do Airbnb utilizando técnicas de data science e modelos de machine learning. A meta é melhorar a qualidade e relevância das descrições dos anúncios, otimizando a experiência do usuário e aumentando as taxas de conversão.

## Visão Geral do Projeto

Com o crescimento do volume de anúncios no Airbnb, descrições precisas e atraentes são cruciais para atrair hóspedes. Este projeto visa prever e gerar automaticamente descrições relevantes com base em diversas características, como tipo de propriedade, comodidades, localização e avaliações de usuários.

## Principais Funcionalidades

Coleta e Pré-processamento de Dados: Coleta e limpeza dos dados dos anúncios do Airbnb, incluindo dados estruturados (ex.: tipo de propriedade, preço, localização) e dados textuais não estruturados (ex.: avaliações, descrições).

Análise Exploratória de Dados (EDA): Realização de uma EDA detalhada para entender padrões, correlações e insights no conjunto de dados.

## Engenharia de Recursos

Criação e seleção de recursos relevantes a partir de dados estruturados e não estruturados para melhorar o desempenho do modelo.

## Modelo de Machine Learning

Implementação e treinamento de modelos de machine learning (ex.: modelos baseados em NLP como TF-IDF, LSTM ou BERT) para prever e gerar descrições textuais.

Avaliação e Ajuste do Modelo: Avaliação do desempenho do modelo usando métricas como acurácia, precisão e recall, e otimização através do ajuste de hiperparâmetros.

## Deploy

O modelo treinado foi implementado em uma interface web acessível via terminal utilizando Streamlit, permitindo que os usuários insiram detalhes dos anúncios e recebam previsões de descrições.

## Tecnologias Utilizadas

Python: Para manipulação, análise de dados e construção do modelo.

Pandas & NumPy: Para pré-processamento de dados e engenharia de recursos.

scikit-learn: Para algoritmos tradicionais de machine learning.

Jupyter Notebook: Para desenvolvimento interativo de código e análise.

Matplotlib & Seaborn: Para visualização de dados.

Streamlit: Para deploy do modelo como uma aplicação web.

## Como Executar o Projeto:

Clone o repositório: git clone https://github.com/seu-usuario/airbnb-text-prediction.git

Instale as dependências necessárias: pip install -r requirements.txt

Execute o notebook Jupyter para EDA e treinamento do modelo: jupyter notebook

Inicie a aplicação web via Streamlit: streamlit run app.py
