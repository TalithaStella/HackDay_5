
## Atenção: 
- Projeto de participação do 5º HackDay da Comunidade DS! 
- Nessa competição todos os times tiveram 48 horas para entregar a melhor performance 


### Índice
* [1. Problema de negócio](#1-problema-de-negócio)
* [2. Planejamento](#2-planejamento)
* [3. Premissas](#3-premissas)
* [4. Análise Exploratória dos Dados](#4-análise-exploratória-dos-dados)
* [5. Machine Learning](#5-machine-learning)
* [6. Resultado da Modelagem para o Negócio](#6-resultado-da-modelagem-para-o-negócio)
* [7. Entrega e Conclusão](#7-entrega-e-conclusão)
* [8. Próximos passos](#8-próximos-passos)

<hr>

## 1 Problema de negócio
A loja de roupas InStyle nos Estados Unidos enfrenta desafios com a experiência do cliente à medida que cresce. Com o aumento de clientes, os processos internos de vendas 
e atendimento sofrem problemas, incluindo dificuldade em determinar as necessidades dos clientes, desafios na identificação do cliente ideal pelo time de marketing e 
sobrecarga nos sistemas devido ao grande volume de acessos, causando quedas no site e no aplicativo. Para enfrentar a questão da satisfação do cliente, um time 
interdisciplinar chamado "War Room" foi criado, e os Cientistas de Dados assumiram a responsabilidade de treinar um algoritmo para classificar os clientes como 
"Satisfeito" ou "Neutro/Insatisfeito". Essa classificação ajudará a equipe a identificar e agir rapidamente com os clientes insatisfeitos, compreendendo suas preocupações 
e buscando soluções para melhorar a experiência de compra e manter a reputação da empresa no mercado.

- Problema de Classificação
<br>

## 2. Planejamento

Como a proposta foi entregar o melhor resultado no menor tempo possível, foi atotada um metodologia mais rápida, que pudesse trazer resultados em pouco tempo. 
Por isso foi optado por 


**Principais Ferramentas utilizadas:** 
- Python: pandas, math, numpy, seaborn, matplotlib, dython
- Machine Learning:  LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, BaggingClassifier, XGBClassifier, KNeighborsClassifier
- Preparação de dados: RobustScaler, MinMaxScaler, LabelEncoder, StandardScaler
- Estatística: Skleanin.metrics ( make_scorer, accuracy_score, recall_score, precision_score, balanced_accuracy_score, f1_score), StratifiedKFold, cross_validate


## 3. Premissas 

A base de dados contém as seguintes colunas: 

- Gender: Gênero do cliente
- Age: Idade do cliente
- Type of Purchase: O tipo de compra
- Store size: O tamanho da loja
- Store distance: Distância até o centro da cidade
- InStore wifi: Nível de satisfação com o Wifi da Loja
- Open/Close time convenient: Nível de satisfação do horário de abertura e fechamento da loja
- Easy of online shopping: Nível de satisfação com a compra online
- Store location: Nível de satisfação com a acesso a loja
- Toilet cleaning:Nível de limpeza dos banheiros
- Dressing room: Nível de satisfação com o provador
- Waiting room: Nível de satisfação do local de espera dentro da loja.
- Kids entertainment: Nível de satisfação do espaço kids
- Seller service: Nível de satisfação com o atendimento dos vendedores
- Showroom: Nível de satisfação com a disposição das roupas no interior da loja
- Self-Store: Nível de satisfação com os guarda-volumes da loja
- Purchase service: Nível de satisfação do atendimento no pagamento
- Inflights Service: Store Service
- Cleanliness: Nível de satisfação com a limpeza da loja
- Carrier delay in minutes: Tempo de atraso do produto na saída da transportadora
- Delivery delay in minutes: Tempo de atraso na entrega do produto até a casa do cliente.

<br>

## 4. Análise Exploratória dos Dados


## 5. Machine Learning


## 6. Resultado da Modelagem


## 8. Próximos passos




