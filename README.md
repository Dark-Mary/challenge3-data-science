<h1 align="center">📊 Challenge TelecomX_2</h1>
<h2 align="center">Análise Preditiva de Evasão de Clientes</h2>


<br/>

## 🔮 Previsão de Churn com Machine Learning

Este repositório reúne a solução para a segunda etapa do desafio da Telecom X, voltada para a construção de modelos preditivos capazes de identificar clientes com maior propensão a cancelar seus serviços. O projeto foi desenvolvido de forma prática, utilizando dados tratados na Parte 1 e aplicando técnicas avançadas de ciência de dados e aprendizado de máquina.

## 🎯 Objetivo do Projeto

A Telecom X enfrenta um cenário de elevada evasão de clientes (churn). Com isso, o desafio teve como metas:

📥 Preparar e limpar os dados para uso em modelos preditivos.

🔎 Explorar variáveis e entender fatores que influenciam a decisão de cancelamento.

🤖 Construir modelos de classificação para prever a evasão.

💡 Gerar insights estratégicos para apoiar ações de retenção de clientes.

🧹 Processamento de Dados

<br/>

As principais etapas da preparação dos dados incluíram:

 * Importação do dataset tratado (Parte 1).

 * Transformação de variáveis categóricas com One-Hot Encoding.
 
 * Tratamento de valores ausentes e inconsistências.

 * Normalização de colunas numéricas para melhorar a performance dos modelos.

 * Seleção de variáveis com base em correlação e relevância.

 * Modelagem Preditiva e Resultados

 * Proporção de churn encontrada: ~26,5% dos clientes cancelaram serviços.
   
 * Modelos testados: Regressão Logística e Random Forest.
 
<br/>

## 🥇 Melhor desempenho:

Regressão Logística apresentou resultados mais consistentes:

Acurácia: 80%

Precisão: 65%

Recall: 52%

F1-score: 58%

## 🔑 Variáveis com maior impacto:

Tempo de contrato (clientes com pouco tempo têm maior risco)

Valor mensal cobrado

Serviços adicionais (segurança online, backup)

## 💡 Estratégias Recomendadas

🎯 Criar campanhas de retenção para clientes em contratos curtos ou com cobranças mensais elevadas.

💰 Oferecer pacotes promocionais e descontos para aumentar fidelização.

📊 Utilizar o modelo preditivo para monitoramento contínuo, permitindo ações preventivas antes do cancelamento.

<br/>

## 🔧 Tecnologias Utilizadas

🐍 Python 3.10+

📦 Pandas, NumPy

🤖 Scikit-learn

📊 Matplotlib, Seaborn

☁️ Google Colab

## ✍️ Autora
Projeto desenvolvido por Mariana Pedro Carvalho como parte do desafio educacional Challenge TelecomX do programa ONE Alura.

## 📝 Licença
Este projeto foi desenvolvido para fins estritamente educacionais.
