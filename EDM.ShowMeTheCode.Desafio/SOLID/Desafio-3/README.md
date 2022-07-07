# Desafio 3 :rocket: 

Suponha que você esteja desenvolvendo uma aplicação web que inclua uma calculadora de impostos on-line.
Os usuárois podem visitar uma página da web, especifiar suas receitas, as deduções e calcular o imposto a pagar.

Para isso você criou a classe **CalcularImposto** e definiu o método **Calcular** que usa como parâmetro o valor, o total das deduções e o pais do usuário.
Para cada país existe uma regra para calcular o imposto.

O método **Calcular()** determina o valor do imposto subtraindo o valor da renda das deduções totais obtendo o **valorBase** para cálculo.

## Diagrama

<img src="Diagrama UML.PNG">

A seguir, conforme o pais do usuário é aplicado a regra para calculuar o imposto do usuário que é retornado na variável **valorImposto**.

## Classe CalcularImposto

<img src="Classe CalcularImposto.PNG">

Atualmente o cálculo é feito apenas para os países: Brasil, USA e Argentina.
Analise o código e pense no que vai acontecer se precisarmos incluir mais dois ou três novos países 
para realizar o cálculo de imposto.

## Tarefas :hammer:

- [ ]  Qual princípio esta implementação está violando?
- [ ]  Explique o motivo da violação.
- [ ]  Proponha uma solução para o problema.
