# Churn Sub

Projeto de Machine Learning para identificação de futuros players que cancelarão sua assinatua na Gamers Club.

Todo desenvolvimento deste projeto será realizado durante as lives ([twitch.tv/teomewhy](https://www.twitch.tv/teomewhy)), utilizando o Databricks, plataforma Big Data amplamente utilizada no mercado de trabalho.

## Motivação

Uma das fontes de receita da GC são as assinaturas de seus players. Com isso, quando há crescimento de churn (cancelamento), é um sinal de que a receita terá queda. Assim, ao identificar os possíveis players que deixarão de assinar, temos oportunidade de retê-los, podendo realizar promoções e adição de benefícios, bem como comunicação de quais funcionalidades ele pode passar a utilizar.

## Dados

Utilizaremos os dados fornecidos pela própria Gamers Club. Você pode baixar estes dados no Kaggle: [Brazilian CS:GO Platform Dataset by Gamers Club](https://www.kaggle.com/datasets/gamersclub/brazilian-csgo-plataform-dataset-by-gamers-club).

Para os assinantes do canal da Twitch, os dados estarão disponíveis no Datalake.

## Agenda

Nossas lives acontecem todas Terças e Quintas as 9:00AM, seguindo o seguinte calendário:

|Encontro|Data|Tema|Link|
|---|---|---|---|
|1|12-07-22|Introdução e definição do problema| [:link:](https://www.twitch.tv/videos/1530063562) |
|2|14-07-22|Definição das Features Store - Parte I | [:link:](https://www.twitch.tv/videos/1531592209) |
|3|19-07-22|Definição das Features Store - Parte II | [:link:](https://www.twitch.tv/videos/1536356016) |
|4|21-07-22|Variável resposta e ABT| [:link:](https://www.twitch.tv/videos/1538383113) |
|5|26-07-22|SEMMA| [:link:](https://www.twitch.tv/videos/1543294104) |
|6|28-07-22|Modelo final| [:link:](https://www.twitch.tv/videos/1545273986) |
|7|02-08-22|Deploy com MLflow| [:link:](https://www.twitch.tv/videos/1551009420) |

Para acessa a coleção completa dos vídeos, [clique aqui](https://www.twitch.tv/collections/-iVyOjw2ARc93A).

### 1. Introdução e definição do problema

Aqui vamos definir qual é a problemática que vamos atuar. Dando um boa introdução de como funciona a Gamers Club e seus assinaturas.
Desta forma o pessoal consegue entender melhor quais serão as oportunidades envolvidas.

### 2. Definição das Features Store

A partir dos dados, podemos identificar quais variáveis (atributos) podem fazer mais sentido para este estudo. A ideia é ao final deste encontro tenhamos as principais features preditoras do churn, em formato de Feature Store.

Feature Store criadas:
- [X] Assinatura
- [X] Gameplay
- [X] Medalha


### 3. Variável resposta e ABT

Uma das etapas mais complicadas no processo de modelagem é a definição e construção da variável resposta, i.e., a variável (evento) que desejamos prever. Neste encontro teremos não só esta definição, mas sua construção e a tabela para o treinamento do nosso algoritmo.

### 4. SEMMA

Ao organizarmos nosso mapa mental sobre o ciclo analítico, as coisas ficam mais fáceis de serem codificadas, isto é, tendo claro quais são os passos necessários a serem seguidos, podemos escrever um código mais limpo e claro. Para ajudar neste entendimento, vamos apresentar o conceito do SEMMA, desenvolvido pelo SAS Institute.

### 5. Modelo Final

Após ter treinado diversos algoritmos e testado diferentes métricas de performance, vamos decidir qual é o melhor algoritmo para explicar o evento de Churn de assinaturas na GC.

### 6. Deploy

Para gerr valor a partir dos dados, é necessário que outros usuários e sistemas possam consumir as informações geradas pelo modelo. Então buscamos realizar o deploy deste algoritmo em forma de Batch e/ou Real Time, seja usando agendadores ou APIs.

## Sobre as lives

Todas lives são abertas ao público em formato gratuito. Ao apoiar nossa iniciativa de ensino, você ganha alguns benefícios:

- Acesso às gravações das lives
- Acesso ao Databricks e aos dados
- Dobro de pontos para resgate de prêmios ao assistir lives
