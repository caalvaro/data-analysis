# Wine Reviews Dataset

Acesse o projeto aqui:

[**Python Notebook - Wine Reviews Dataset**](https://github.com/caalvaro/data-analysis/blob/main/Data%20processing%20-%20Wine%20Reviews%20Dataset/Data%20processing%20-%20Wine%20Reviews%20Dataset.ipynb)

## Objetivo
Extrair diversas entidades e relacionamentos a partir de uma tabela única de reviews, obtendo tabelas para popular um banco de dados mais conciso e estruturado de acordo com a modelagem abaixo.

![Modelo Entidade-Relacionamento](https://raw.githubusercontent.com/caalvaro/data-analysis/main/Data%20processing%20-%20Wine%20Reviews%20Dataset/wine_dataset_model.png)

## Ferramentas utilizadas
Bibliotecas do Python: **Pandas** e **Json**

## Desafios e aprendizados
A primeira versão do projeto foi feita usando uma abordagem bem mais ingênua, iterando sobre as linhas para analisar uma a uma e registrar as relações entre as tabelas. Além de ser uma solução menos enxuta, ela era demorada pois dependia de várias execuções do método "query" do Pandas.

Na segunda versão, pude explorar o uso dos métodos **Map, Applymap e Explode** do Pandas, que permitem fazer processamentos dos dados muito mais rapidamente.

## Resultados
A partir da tabela inicial, foram geradas 8 novas tabelas, considerando as entidades e as tabelas pivot para relacionamentos n:n. O resultado foram dados muito mais organizados e estruturados de forma padronizada, facilitando a consulta, análise e manutenção.

 - user manufacturer
 - product
 - categorie
 - store
 - review
 - product_categorie
 - product_store
