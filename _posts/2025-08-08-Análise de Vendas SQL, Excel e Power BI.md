---
layout: post
title: "Análise de Vendas com SQL, Excel e Power BI"
date: 2025-08-08 18:00:00 -0300
author: Rony Vonn Santos
categories: Análise de dados 
image: assets/images/post/dash.png
---

# **Introdução**

No dinâmico mercado atual, a compreensão aprofundada do comportamento de vendas é crucial para o sucesso empresarial. Este projeto teve como objetivo analisar um conjunto abrangente de dados de vendas para identificar as categorias de produtos mais vendidos, avaliar o desempenho de vendas ao longo do tempo e mapear as regiões com maior faturamento.



____________________________________________________________________________________________________

# **Metodologia** 

Para alcançar esses resultados, utilizei o banco de dados público AdventureWorksDW2022 (Microsoft), realizando:

•
SQL Server: Extração e manipulação de dados brutos. A complexidade dos dados foi sanada através da união (Joins) das tabelas do Schema Snowflake, este tipo de modelagem de dados é normalizada, ou seja, as tabelas de dimensões são divididas em várias menores, evitando dados repetidos. Com isso obtém-se menor custo de armazenamento, mas, em contrapartida há perda significativa de performance. 

Para um modelo Flat Table, os dados ficam em uma única tabela (fato + dimensões), sem que haja normalização. Como desvantagem, há maior redundância e, consequentemente, um maior custo em armazenamento, por outro lado ganha-se simplicidade na análise e melhor desempenho. Vale ressaltar que o custo de armazenamento hoje é relativamente baixo se comparado ao custo de processar queries complexas.

Confira abaixo, o diagrama criado no SQL Server com o modelo Snowflake:

![Diagrama do modelo Snowflake]({{ site.baseurl }}/assets/images/post/diagrama_modelo_snowflake.png)

•
Excel: Apoio na limpeza, padronização e conferência de dados, permitindo a validação cruzada e a organização inicial, garantindo a integridade dos dados antes da visualização.

Confira abaixo, o modelo Flat Table com os dados já consolidados em um Dataset Excel:

![Dataset do modelo Flat Table]({{ site.baseurl }}/assets/images/post/dataset_modelo_flat_table.png)

•
Power BI: A etapa final envolveu a criação de Dashboards interativos no Power BI. Desenvolvi métricas chave como 'Número de Vendas' e 'Faturamento Total', além de visualizações ricas em gráficos de barras, linhas, mapas e roscas, facilitando a exploração dos dados e a identificação de tendências de forma intuitiva.


____________________________________________________________________________________________________

# **Conclusão**

Mesmo com um escopo aparentemente simples, este projeto demonstrou o poder da análise de dados para extrair Insights relevantes e acionáveis. A combinação estratégica de SQL Server para tratamento, Excel para conferência e Power BI para visualização permitiu transformar dados brutos em informações estratégicas de alto valor. Identifiquei padrões de vendas, sazonalidades e as regiões de maior desempenho, fornecendo uma base sólida para decisões de negócio. 

Esta experiência reforça a importância de unir rigor técnico, organização e clareza visual na apresentação de dados. A capacidade de transformar números em narrativas compreensíveis é uma habilidade inestimável, e este projeto aprimorou significativamente minha proficiência em todo o ciclo de vida da análise de dados, desde a extração até a visualização final.


____________________________________________________________________________________________________

### **Repositório Oficial dos Dados**

Repositório oficial dos dados: [Microsoft SQL Server Samples](https://github.com/microsoft/sql-server-samples)


____________________________________________________________________________________________________
### **Recursos do Projeto:**

Query utilizada, disponível no GitHub: [Acesse meu GitHub](https://github.com/ronycosta01/An-lise-de-Vendas)

Arquivos .xlsx e .pbix, disponíveis para download no Google Drive: [Veja os arquivos](https://drive.google.com/drive/folders/1NcCICh9J4yQsVpQElAtgZ-w_HeNUlCjv?usp=sharing)

