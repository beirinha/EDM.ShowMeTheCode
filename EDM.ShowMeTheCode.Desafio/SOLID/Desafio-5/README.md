# Desafio 5 :rocket: 

Temos aqui o código de uma classe **Pizzaria** que cria piizzas de diversos sabores usando o método **CriarPizza()**
que recebe uma ***string*** para indicar o tipo da pizza que deverá ser criado.

`
class Pizzaria
    {
        private Pizza pizza;
        public void CriarPizza(string tipo)
        {
            if (tipo.Equals("mussarela"))
            {
                pizza = new PizzaMussarela();
            }
            else if (tipo.Equals("calabresa"))
            {
                pizza = new PizzaCalabresa();
            }
        }
    }
`

## Tarefas :hammer:

- [ ] Identifique os problemas apresentados por este código.
- [ ] Indique os princípios que estão sendo violados.
- [ ] Altere o código implementado para uma solução aderente ao SOLID, criando classes e/ou interfaces necessárias para isso.

### Dicas :bulb:
- Defina a classe **Pizza** commo classe base das classes concretas **PizzaMussarela** e **PizzaCalabresa**
- Encapsule o código usado para criar as pizzas em outro objeto.