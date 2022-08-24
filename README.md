# Modulo_2_P1_Regressaoo_Linear
Curso Ciência de dados da Blue Edtech - Predição da precificação de casas

# Projeto 1 - Predição da precificação de casas
  - House Sales in King County, USA - Kaggle
  
## Entrega
  - O projeto deve ser entregue até a segunda-feira da 3ª semana de aula, envie o link do GitHub ou HTML na atividade no Moodle.
  - O prazo máximo é terça-feira da 3ª semana de aula, valendo 20% a menos da nota.

## Dados do Certificado
  - Linguagem: Python
  - Tecnologias: Pandas, Numpy e Sklearn
  - Carga horária: 20 horas

## Introdução
  - Este é um conjunto de dados armazenado no Kaggle, uma plataforma de estudo e competições de Ciência de Dados. Segue a tradução sobre o conjunto de dados.
"Este conjunto de dados contém preços de venda de casas para King County, que inclui Seattle. Inclui casas vendidas entre maio de 2014 e maio de 2015."

  - Segue a descrição das variaveis:
     - id - identificação unica para cada venda
     - date - data da venda
     - price - preço da venda
     - bedrooms - número de quartos
     - bathrooms - número de banheiros
     - sqft_living - tamanho da casa em metros quadrados
     - sqft_lot - tamanho do lote em metros quadrados
     - floors - número de andares
     - waterfront - vista para praia
     - view - visitado
     - condition - condição da casa
     - grade - nota de qualidade (baseado no sistema de classificação do King County)
     - sqft_above - tamanho da área abaixo da casa em metros quadrados
     - sqft_basement - tamanho do porão em metros quadrados
     - yr_built - ano de construção
     - yr_renovated - ano da ultima reforma
     - zipcode - CEP
     - lat - latitude
     - long - longitude
     - sqft_living15 - área da casa em 2015 (implica a algumas reformas). Isso pode ou não ter afetado a área do lote
     - sqft_lot15 - área do lote em 2015 (implica a algumas reformas)

## Sobre este projeto
  - Este é o seu primeiro projeto usando Ciência de Dados. Neste projeto treine os conhecimentos aprendidos até o momento e que entenda algumas das dificuldades que   pode ter quando for aplicar os mesmos.
  - Os principais pontos que serão avaliados:
     - Levantamento de hipoteses
     - Manipulação de dados e criação de gráficos simples com o Pandas
     - Criar um modelo usando regressão linear e justificar
     
## Preparação do ambiente
  - Acessem o link - https://www.kaggle.com/datasets/harlfoxem/housesalesprediction e logo abaixo cliquem em "Download". Caso voce não tenha uma conta no Kaggle, crie uma e retorne para esse ponto para realizar o download.

## Exercicio 1. (0.5 pontos)
  - Formule ao menos duas perguntas que você acha que poderiam ser respondidas usando os dados

## Exercicio 2. (2.5 pontos)
  - A capacidade de comunicação é um dos principais pontos na análise de dados, pois sua análise deve ser tão boa quanto a sua capacidade de comunicá-la. Para isso usamos tabelas resumo e gráficos para apresentar os principais achados do trabalho realizado. Podemos adicionar outros materias que possam aprofundar essa apresentação como artigos e outros estudos realizados.
Assim, qual visualização você acha interessante destacar?

## Exercicio 3. (3 pontos)
  - Faremos uma analise exploratoria sobre estes dados, preencha abaixo analises sobre o conjunto de dados. Para isso a biblioteca numpy para obter a contagem, média, mediana e os quartis.
  - Neste conjunto de dados há casas com tamanho muito acima ou abaixo do esperado (outliers)? Faça um gráfico de caixa (boxplot) do tamanho das casas.
  - Observando a sua visualização, há casas com tamanhos muito abaixo ou acima do esperado (outliers)?

## Exercicio 4. (4 pontos)
  - Construa um modelo de regressão linear para predizer a variável price (preço) com statsmodels.api.
  - Coloque abaixo a saida do seu modelo usando seu_modelo.summary().
  - Faça outro modelo usando a biblioteca sklearn.
  - Qual o valor de R² e MAE obtido?
  - Faça novamente um novo modelo utilizando a seleção de caracteristicas, selecionando as 5 variaveis mais importantes.
  - Quais são as 5 variaveis mais importantes deste conjunto de dados?
  - Qual o valor de R² e MAE odeste novo modelo? Este modelo é melhor do que o anterior?

