🚗 Classificação de Acidentes de Trânsito na Paraíba utilizando KNN
📌 Visão Geral

Este projeto tem como objetivo desenvolver um modelo de classificação supervisionada para prever a gravidade de acidentes de trânsito no estado da Paraíba, a partir de dados oficiais disponibilizados pela Polícia Rodoviária Federal (PRF).

A abordagem adotada utiliza o algoritmo K-Nearest Neighbors (KNN), explorando padrões presentes nas características dos acidentes para inferir sua classificação.

📊 Fonte de Dados

Os dados foram obtidos por meio do portal de dados abertos da PRF:

🔗 https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf

O conjunto contém informações detalhadas sobre ocorrências de acidentes em rodovias federais brasileiras.

🎯 Objetivo do Modelo

Construir um modelo capaz de prever a variável:

classificacao_acidente

com base em atributos observacionais relacionados ao contexto do acidente.

🧾 Variáveis Explicativas

Foram selecionadas variáveis categóricas relevantes do ponto de vista operacional e interpretativo:

sexo

tipo_envolvido

tipo_acidente

condicao_metereologica

fase_dia

estado_fisico

Essas variáveis capturam aspectos comportamentais, ambientais e circunstanciais associados aos acidentes.

⚙️ Metodologia

A construção do modelo seguiu as seguintes etapas:

Aquisição e carregamento dos dados

Pré-processamento, incluindo tratamento de valores ausentes e codificação de variáveis categóricas

Seleção de atributos com base em relevância prática

Divisão dos dados em conjuntos de treino e teste

Treinamento do modelo KNN

Avaliação de desempenho utilizando métricas de classificação

O algoritmo KNN foi escolhido por sua simplicidade, interpretabilidade e eficiência em problemas com estruturas de proximidade bem definidas.

📈 Resultados

O modelo apresentou desempenho consistente no conjunto de teste:

Acurácia: 84%

Esse resultado indica boa capacidade preditiva, considerando a natureza categórica e potencialmente desbalanceada dos dados.

📊 Avaliação

A avaliação do modelo foi conduzida com base em:

Matriz de confusão

Acurácia global

Análises adicionais podem incluir métricas como precisão, recall e F1-score para melhor compreensão do desempenho por classe.
