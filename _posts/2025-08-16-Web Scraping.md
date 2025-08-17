---
layout: post
title: "Web Scraping"
date: 2025-08-16 20:00:00 -0300
author: Rony Vonn Santos
categories: "Análise_de_dados"
image: assets/images/post/dash_mathplotlib.png
---


# **Introdução**

Estava à procura de projetos que fizessem sentido na área de Análise de Dados, então encontrei um tal de Web Scraping, assunto muito comentado.  A princípio não sabia como fazer, mas sempre gostei de um desafio! Uni meus conhecimentos em Python, Pandas e automação Web, com o desejo de aprender algo novo, veja só o resultado.

A automação da coleta e análise de informações é uma habilidade essencial para transformar dados em conhecimento aplicável.
Este projeto teve como objetivo realizar Web Scraping em um site estático de E-Commerce (Books to Scrape) para coletar dados sobre livros, incluindo título, preço e disponibilidade em estoque e em seguida, aplicar análise exploratória básica a fim de compreender o comportamento desses produtos.



____________________________________________________________________________________________________

# **Metodologia** 

Para chegar ao resultado final, que é a parte visual, utilizei as seguintes etapas e tecnologias:

•
Coleta de Dados (Web Scraping): utilizei Selenium para extrair as informações diretamente do HTML do site. A automação permitiu a navegação entre páginas e a coleta contínua de dados como título, preço e estoque.

•
Tratamento e Organização (Pandas): Os dados coletados foram organizados em DataFrames, passando por uma etapa de limpeza (remoção de caracteres indesejados, conversão de tipos numéricos, padronização de colunas).
Também foram calculadas estatísticas descritivas, como preço médio e livro mais caro.

Confira abaixo, os dados armazenados em DataFrames:

Dados sem tratamento:

![Dataframe sem tratamento]({{ site.baseurl }}/assets/images/post/dataframe_sem_tratamento.png)

Dados já tratados e corretamente tipados:

![Dataframe tratado]({{ site.baseurl }}/assets/images/post/dataframe_tratado_tipado.png)

•
Visualização (Matplotlib):
Foram criados gráficos de barras para os Top 5 livros mais caros, histogramas de preços e gráfico de dispersão para análise de relação entre preço e quantidade em estoque, possibilitando identificar padrões de distribuição e destacar insights relevantes sobre o catálogo de livros.

![Dash com Matplotlib]({{ site.baseurl }}/assets/images/post/dash_mathplotlib.png)

•
Documentação (Jupyter Notebook):
Todo o processo foi realizado no Jupyter Notebook (.ipynb), escolhido pela organização em blocos de código e pela facilidade de incluir explicações em blocos no formato Markdown durante o desenvolvimento.



____________________________________________________________________________________________________

# **Conclusão** 

Esse foi meu primeiro projeto prático de Web Scraping, no qual pude unir Python, automação, manipulação e análise de dados.
Os principais resultados foram:

•
Identificação da faixa de preços mais comum entre os livros.

•
Descoberta dos livros mais caros e da respectiva quantidade em estoque no catálogo.

•
Visualização clara da distribuição de preços.


Essa experiência consolidou meu aprendizado em Python, Pandas, Selenium e visualização de dados, além de demonstrar a importância de estruturar corretamente o processo de coleta e análise para transformar informações brutas em insights estratégicos.


____________________________________________________________________________________________________

### **Site utilizado para aprendizado do Web Scraping**

Site utilizado para aprendizado do Web Scraping: [Books to Scrape](https://books.toscrape.com/)


____________________________________________________________________________________________________

### **Recursos do Projeto:**

Código-fonte, disponível no GitHub: [Acesse meu GitHub](https://github.com/ronycosta01/Web-Srcaping/blob/main/web_scrapping.ipynb)