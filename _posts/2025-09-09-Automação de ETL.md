---
layout: post
title: "Automação de ETL"
date: 2025-09-09 18:00:00 -0300
author: Rony Vonn Santos
categories: "Automação_e_ETL"
image: assets/images/post/banco_populado.png
---


# **Introdução**

Quem está começando na área de Análise de Dados, TI ou quer aprender novas habilidades com tecnologia, sabe da dificuldade em encontrar bases de dados completas, reais e bem estruturadas para praticar. Foi nesse contexto que descobri o Kaggle, uma plataforma repleta de datasets gratuitos, ideal para estudantes que desejam praticar SQL, Python ou Data Science em geral.

Pensando nisso, desenvolvi este projeto como uma forma de aplicar minhas habilidades e também como contribuição para quem tinha entraves e procurava por ideias práticas: abordarei como é possível encontrar bons datasets no Kaggle e criei uma automação de ETL simples importação, tratamento e inserção em um banco de dados relacional.

Esse fluxo, mesmo em um exemplo inicial, já reflete um cenário real de pipelines de dados, em que a organização e a consistência das informações são fundamentais para análises futuras.



____________________________________________________________________________________________________

# **Metodologia**

O projeto foi dividido em 4 etapas principais:

•
Pesquisa por uma plataforma completa que, além de disponibilizar datasets, também possui trilhas de aprendizagem, discussões com comunidades, competições e muito mais.

•
Modelagem do Banco de Dados: foi estruturado um esquema relacional adequado ao dataset, definindo chave e tipos de dados para assegurar a integridade da informação.

Estrutura da tabela ainda sem dados:

![Banco sem dados]({{ site.baseurl }}/assets/images/post/banco_sem_dados.png)

•
Tratamento e Organização (Pandas): os dados foram importados, limpos e transformados. Essa etapa incluiu conversão de tipos e padronização de colunas, garantindo que o conteúdo estivesse pronto para ser carregado no banco.

![DataFrame tratado]({{ site.baseurl }}/assets/images/post/dataframe_tratado.png)

•
Automação da Inserção (Python + SQL): com a biblioteca pyodbc, foi criada uma conexão em Python capaz de conectar-se ao banco e inserir os dados de forma automática. Isso simula um fluxo de ETL em que a etapa de Load acontece sem necessidade de manipulação manual.

![Execução da automação]({{ site.baseurl }}/assets/images/post/comando_execucao.png)



____________________________________________________________________________________________________

# **Conclusão**

Esse projeto me permitiu descobrir uma vasta fonte de dados, compreender melhor como funciona o processo de integração entre datasets e bancos de dados, fortalecendo meu aprendizado em:

•
Modelagem relacional e boas práticas de estruturação de tabelas.

•
Tratamento de dados com Pandas para adequação a formatos compatíveis com SQL.

•
Automação de processos de inserção utilizando Python, simulando um fluxo ETL real.

Dessa forma, consegui ir além da análise exploratória e visualização, mostrando a importância da engenharia de dados como base sólida para qualquer processo analítico.



____________________________________________________________________________________________________

### **Link da plataforma Kaggle**

Link da plataforma Kaggle: [kaggle](https://www.kaggle.com/)


____________________________________________________________________________________________________

### **Recursos do Projeto:**

Script de criação do banco de dados, disponível no GitHub: [Acesse meu GitHub](https://github.com/ronycosta01/Automa-o-de-ETL/blob/main/criacao_do_banco.sql)

Script (ipynb) de todo o fluxo de automação, disponível no Github: [Acesse meu GitHub](https://github.com/ronycosta01/Automa-o-de-ETL/blob/main/automacao.ipynb)

Arquivo .csv usado, disponível para download no Google Drive: [Veja o arquivo](https://drive.google.com/drive/folders/10zw5R8KNMe7Arqije9zOKylB-dLHrneF?usp=sharing)