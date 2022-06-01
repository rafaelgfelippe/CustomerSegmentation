![](figures/BigRango.png)

Este é um projeto de clusterização.

O conjunto de dados utilizado está disponível [neste link](https://www.kaggle.com/rafaelgfelippe/food-delivery).

[![forthebadge made-with-R](figures/R.png)](https://www.r-project.org/)

# Entendimento do Negócio

A Big Rango é um restaurante do tipo *Dark Kitchen*, ou seja, é um estabelecimento de serviço de alimentação que oferece apenas comida para viagem. Atuando em 9 cidades, a Big Rango é um restaurante 100% delivery, onde os pedidos são realizados via telefone ou internet, e entregues diretamente aos clientes.

Visando oferecer uma comunicação assertiva e personalizada, a Big Rango contratou um consultor em ciência de dados para realizar a segmentação de seus clientes. O principal objetivo da empresa é identificar os principais padrões de consumo e assim, realizar campanhas de Marketing customizadas para cada grupo de clientes. 

Além disso, a empresa também estuda adicionar novos pratos no cardápio, que atualmente, é composto por pizzas, bebidas, saladas e sobremesas. A segmentação dos clientes também pode auxiliar a empresa nessa tarefa. 

# Dicionário de Dados

Em relação ao conjunto de dados, as seguintes informações foram disponibilizadas:

- Os dados estão em formato estruturado e serão disponibilizados em um arquivo "csv".
- A variável id_transacao possui o mesmo código para cada item dentro de um pedido.
- Todos os pedidos são referentes ao ano de 2019.
- A empresa não trabalha das 2 as 10 horas da manhã.

Além disso, também foi disponibilizado o dicionário de dados:

| Variáveis                        | Descrição                                                    |
| -------------------------------- | ------------------------------------------------------------ |
| id_transacao                     | Identificação do pedido                                      |                          
| horario_pedido                   | Horário do pedido                                            |
| localidade                       | Local da unidade do restaurante                              |
| nome_item                        | Nome do item pedido                                          |
| quantidade_item                  | Quantidade do item no pedido                                 |
| latitude                         | Latitude da localidade do restaurante                        |
| longitude                        | Longitude da localidade do restaurante                       |

# Estratégia da Solução

Como estratégia para a solução dos problemas, definimos as seguintes etapas:

- **1. Entendimento do Negócio:** nesta etapa inicial, realizamos uma breve introdução sobre o tema do projeto, entendemos as necessidades do cliente e definimos nossos objetivos.

- **2. Entendimento dos Dados:** o objetivo é realizar um tratamento inicial para verificar a qualidade dos dados, também realizaremos uma análise mais detalhada a fim de responder perguntas sobre o negócio.

- **3. Engenharia de Atributos:** nessa sessão, iremos visualizar os dados de uma outra perspectiva, além de realizar a seleção das melhores variáveis.

- **4. Pré-Processamento dos Dados:** nesta etapa, o objetivo é preparar os dados para a aplicação do modelo de Machine Learning.

- **5. Modelagem Preditiva:** utilizaremos o K-means, um dos algoritmos mais utilizados para problemas de clusterização.

- **6. Análise de Clusters:** iremos explorar os clusters com objetivo de identificar padrões e recomendar ações para a área de Marketing.

- **7. Conclusões Finais:** por fim, entregaremos o resultado final do projeto.

# TOP 3 Insights 

**P1. Qual o mês que teve o maior e o menor número de pedidos?**
Maio foi o mês que teve o maior número de pedidos, enquanto fevereiro registrou o menor número.
![](figures/P1.png)
