# Modelo de análise das métricas RFV
Modelo de análise das métricas RFV usando modelo de Clustering para criar um sistema de agrupamento de perfis de clientes para um e-commerce.

## Contexto

Você foi contratado por uma empresa de e-commerce que está buscando entender melhor o comportamento de seus clientes para personalizar as suas campanhas de marketing. Para isso, a empresa disponibilizou uma base de dados em csv contendo dados sobre clientes, produtos e transações da loja realizadas entre os anos de 2010 e 2011.

Com base nesses dados, você precisa agrupar os clientes em clusters com base em seu comportamento de compra. Isso irá permitir identificar padrões e características em comum entre os clientes, como:

- Clientes que compram os mesmos produtos;
- Clientes que possuem a mesma frequência de compras;
- Clientes que gastam mais dinheiro em suas compras.

A partir desses clusters, gere insights para que a empresa possa segmentar melhor a sua base de clientes e personalizar as suas campanhas de marketing, direcionando promoções e ofertas aos clientes com base no comportamento de compras.

### Sobre os dados

Os dados fornecidos possuem informações de transações de compras de uma loja de e-commerce em 38 países e territórios, com mais de 4.000 clientes únicos e mais de 540.000 transações.

Atenção: as datas estão no formato MM/DD/YYYY HH:mm:ss; existem dados nulos que precisam ser tratados antes da realização da análise; por mais que os códigos de identificação sejam numéricos, o modelo não pode considerá-los como grandezas numéricas.

# 🎯 Etapas de Desenvolvimento

## **Etapa 01) Análise exploratória dos dados**

1. Carregue a base de dados;
2. Realize uma descrição estatística dos dados;
3. Visualize as distribuições e identifique a relevância das colunas para a análise;
4. Verifique a presença de dados nulos, duplicados, outliers e demais inconsistências nos dados.

<aside>
💡**Dica:** certifique-se de que os dados estejam no formato ideal para as análises; por mais que os códigos de identificação sejam numéricos, sua análise não pode considerá-los como grandezas numéricas.

</aside>

## Etapa 02) Pré-processamento dos dados

1. Realize a normalização dos dados
2. Faça uma seleção das variáveis mais relevantes para o modelo;
3. Remova os dados nulos, duplicados, outliers e inconsistentes

## Etapa 03) Selecione um algoritmo de clusterização

1. Escolha um algoritmo adequado para base de dados, como o K0Means, DBSCAN, Hierarquia ou Mean Shift
2. Encontre a quantidade ideal de clusters através dos métodos de Elbow ou Silhouette Score
3. Implemente o algoritmo escolhido

## Etapa 04) Analise os clusters obtidos

1. Identifique os padrões e características em comum entre os clientes
2. Plote gráficos para auxiliar na análise

## Etapa 05) Interpretação dos resultados obtidos

1. Descreva o perfil de compras dos clientes de cada cluster
2. Justifique como essa análise pode ser útil para empresa para segmentação de seus clientes e personalização das campanhas de marketing
3. Sugira ações possíveis com base nas ações realizadas

   # Dica: Evite sequências longas de código sem explicação do que está sendo realizado. Pense que essa documentação está sendo apresentada para o cliente final, seu modelo não pode ser uma “caixa preta”.
