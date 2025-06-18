# Projeto_DataScience
Predição de Churn em Telecom com Machine Learning
Projeto final desenvolvido para o curso de Data Science da Coderhouse.

Storytelling: O Desafio do Negócio
Imagine uma grande operadora de telecomunicações enfrentando uma crise silenciosa: a cada mês, centenas de clientes estão cancelando seus serviços.

Cada cliente perdido representa não apenas uma queda no faturamento, mas também um aumento nos custos para adquirir novos consumidores, que são muito mais altos do que os custos para reter os existentes.

O time de Business Intelligence da empresa foi acionado com perguntas cruciais:

Por que os clientes estão saindo?
Quem são os clientes mais propensos a cancelar?
Como podemos agir de forma antecipada para reverter esse movimento?
Como cientista de dados, nosso desafio é transformar dados brutos em inteligência acionável. Fomos encarregados de construir um modelo preditivo que não apenas identifique os clientes em risco, mas que também forneça insights para que a empresa possa criar campanhas de retenção mais eficazes e personalizadas.

 Descrição do Projeto
Este projeto tem como objetivo prever o Churn (cancelamento de clientes) em uma empresa de telecomunicações, utilizando técnicas de Análise Exploratória de Dados (EDA), Machine Learning e avaliação de desempenho de modelos.

Foram aplicadas diversas etapas de pré-processamento, visualização e modelagem, com o uso de Regressão Logística, Análise de Componentes Principais (PCA), Otimização com GridSearchCV e métricas de avaliação como AUC, F1-Score e Matriz de Confusão.

 Tecnologias Utilizadas
Python 3.x

Pandas

NumPy

Scikit-Learn

Seaborn

Matplotlib

Jupyter Notebook / Google Colab

 Estrutura do Projeto
bash
Copiar
Editar
Projeto_Churn_Coderhouse
Projeto_Churn_Coderhouse.ipynb   # Notebook completo e comentado
Projeto_Churn_Coderhouse.pptx    # Apresentação em PowerPoint
WA_Fn-UseC_-Telco-Customer-Churn.xlsx   # Dataset da IBM (se permitido subir)
README.md                       
# Este arquivo
Etapas do Projeto
Introdução ao Problema de Churn

Aquisição e Entendimento dos Dados

Análise Exploratória de Dados (EDA)

Pré-processamento

Seleção de Variáveis

Visualização com PCA

Modelagem com Regressão Logística

Otimização com GridSearchCV

Avaliação de Desempenho

Conclusões e Próximos Passos

 Principais Resultados
O modelo final obteve uma boa capacidade de previsão de churn com base nas variáveis históricas dos clientes.

Foi aplicada uma otimização de hiperparâmetros usando GridSearchCV.

As principais variáveis relacionadas ao churn incluem: tipo de contrato, tempo de serviço e valor da cobrança mensal.

O desempenho do modelo foi avaliado por meio de:
 Curva ROC (AUC)
 Matriz de Confusão
 Métricas de F1-Score, Precisão e Recall

 Principais Gráficos e Análises
Distribuição de Churn

Top 10 variáveis com maior correlação com o Churn

Visualização PCA (clientes com e sem churn)

Curva ROC

Matriz de Confusão

Métricas de Desempenho

 Dataset Utilizado
IBM Telco Customer Churn Dataset
Link: https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/

 Como Executar o Projeto no Google Colab
Faça o upload do arquivo .ipynb no Google Colab.

Faça o upload do dataset .xlsx.

Execute as células sequencialmente.

 Próximos Passos (Futuros Trabalhos)
Testar algoritmos mais avançados (Random Forest, XGBoost).

Implementar um sistema de alertas para times de retenção.

Realizar deploy como API para uso em produção.

 Autor
Kauan Rios de Melo
Projeto Final - Curso de Data Science - Coderhouse (2025)
