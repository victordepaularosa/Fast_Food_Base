# BASE FAST FOOD DOCUMENTAÇÃO

<AUTOGENERATED_TABLE_OF_CONTENTS>

- EM ATUALIZAÇÃO

## Objetivo

Realizar o tratamento dos dados a partir do dataset do Kaggle de informações de restaurantes de Fast Food baseado na arquitetura medalhão de tratamento de dados, a partir da base nutricional de vários produtos das redes populares de fast food.

 Este conjunto de dados visa esclarecer o valor nutricional destes produtos de fast food, ajudando os consumidores a tomar decisões mais informadas sobre as suas escolhas alimentares.Com informações sobre calorias, gorduras, carboidratos, proteínas e outros nutrientes essenciais, este conjunto de dados fornece um recurso valioso para nutricionistas

## Arquitetura de Dados

A seguir o Diagrama do presente projeto no Databricks Community.

<center>
<img src="imagens\diagrama_fast_food.png">
Diagrama da Estrutura de Dados.
</center>

### Organização no Databricks

Para organizar o projeto foi utilizada a estrutura de data lake do Databricks e além disso a organização dos notebook, conforme as imagens a seguir.

<center>
<img src="imagens\estrutura_data_lake.png">
Organização de Data Lake do Databricks.
</center>

<center>
<img src="imagens\estrutura_notebooks.png">
Estrutura dos Notebooks.
</center>

## Etapas de Tratamento

Conforme apresentado na arquitetura de dados o projeto foi criado na arquitetura medalhão (bronze, silver e gold), tendo o intuito de cada uma das etapas realizar um dos processos de tratamento e do processo de ETL ("Extrair, Carregar, Transformar"), conforme apresentado nos itens abaixo:

1 - Bronze - Realizar a extração de dados da base de dados do Kaggle.

2 - Silver - Realizar as transformações dos dados e a segmentação das tabelas.

3 - Gold - Realizar o relacionamento entre as tabelas dimensões com a tabela fato de fast food.


## Camada Bronze

## Camada Silver

## Camada Gold
