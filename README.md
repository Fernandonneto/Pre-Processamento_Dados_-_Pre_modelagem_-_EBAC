# 🧠 Pré-modelagem: Análise dos serviços e fatores que influenciam o pagamento mensal e o churn

Este projeto faz parte da segunda atividade de pré-modelagem de dados do curso de Cientista de Dados da EBAC e tem como objetivo aplicar técnicas de análise exploratória (EDA) para entender quais serviços impactam o valor mensal pago pelos clientes e identificar variáveis relevantes relacionadas ao churn. Foram utilizadas ferramentas como Python, Pandas e Plotly Express para geração de visualizações interativas.

A atividade analisa um conjunto de dados de uma empresa de telecomunicações para identificar como os serviços contratados influenciam o Monthly_Payment e quais fatores exercem maior impacto no Churn, ou seja, na permanência ou saída do cliente.

## 🧩 Etapas Desenvolvidas

**1. Seleção dos serviços a serem avaliados:** definição dos serviços a serem comparados com o valor mensal.

**2. Geração de Boxplots:** criação de gráficos comparando clientes que possuem ou não cada serviço com seus respectivos pagamentos mensais.

**3. Avaliação de impacto no pagamento:** interpretação das diferenças nas medianas e distribuições entre os grupos “Yes” e “No”.

**4. Identificação das variáveis importantes para churn:** análise dos fatores que mais se relacionam com o cancelamento dos clientes.

## 📊 Resultados e Insights

Durante a análise, foi possível:

- Verificar que Streaming_TV e Technical_Support são os serviços que mais aumentam o valor mensal pago pelos clientes.

- Observar que, para esses serviços, o grupo “Yes” apresenta medianas mais altas e maior dispersão no pagamento.

- Identificar que as variáveis mais relevantes para explicar o churn são:
    - Contract_Type
    - Monthly_Payment
    - Time_as_Customer
    - Serviços utilizados (Technical_Support,       Security_Service, Streaming_TV, Phone_Service)

Esses fatores ajudam a compreender o comportamento dos clientes e são essenciais para a etapa de modelagem preditiva.

## ✅ Conclusão

O projeto reforçou a importância da análise exploratória na pré-modelagem, permitindo identificar quais serviços influenciam diretamente os custos e quais variáveis são fundamentais para explicar o churn. As visualizações geradas mostraram-se eficazes para revelar padrões relevantes e apoiar decisões baseadas em dados.
