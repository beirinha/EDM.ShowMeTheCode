# Desafio 1 :rocket: 

Você tem em uma aplicação uma classe concreta **Cliente** que representa seu modelo de dominio
e que possui as propriedades: **Nome, Pais e Email**
e o método estático **GetClientes** que retorna uma lista de clientes.

A apliacação também possui uma classe **LocalizaCliente** que permite localizar 
o cliente pelo nome e pelo pais e para isso esta classe usa os metodos:
**ProcuraPorPais(string pais)** e **ProcuraPorNome(string nome)**

Após algum tempo foi implementado a funcionalidade parar exportar os dados dos clientes
no formato CSV(Comma Separated Values) e isso foi feito incluindo o metodo
**ExportarCSV** na classe **LocalizaCliente**.

## Diagrama UML

<img src="Diagrama LocalizaCliente.PNG">

## Tarefas :hammer:

- [ ]  Quais principios do SOLID foram violados?
- [ ]  Proponha uma solução.
