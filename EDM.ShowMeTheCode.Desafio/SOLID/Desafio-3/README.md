# Desafio 3 :rocket: 

Suponha que você esteja desenvolvendo uma apliação web que inclua ua calculadora de impostos on-line.
Os usuárois podem visitar uma página da web, especifiar suas receitas, as deduções e aclular o imposto a pagar

Para isso você criou a classe **CalcularImposto** e definiu o método **Calcular** que usa como parâmetro o valor, o total das deduções e o pais do usuário.
Para cada país existe uma regra para calular o imposto.

O método **Calcular()** determina o valor do imposto subtraindo o valor da renda das deduções totais obtendo o **valorBase** para cálculo.

Diagrama
![Diagrama](SOLID/Desafio-3/Diagrama UML.PNG)

A seguir, conforme o pais do usuário é aplicado a regra para calculuar o imposto do usuário que é retornado na variável **valorImposto**.

Classe CalcularImposto
![Classe CalcularImposto](SOLID/Desafio-3/Classe CalcularImposto.PNG)

Atualmente o cálculo é feito apenas para os países: Brasil, USA e Argentina.
Analse o código e pense no que vai acontecer se precisarmos incluir mais dois ou três novos países 
para realizar o cálculo de imposto.

## Tarefas :hammer:

- [ ]  Qual princípio esta immplementação está violando?
- [ ]  Explique o motivo da violação.
- [ ]  Proponha uma solução para o problema.