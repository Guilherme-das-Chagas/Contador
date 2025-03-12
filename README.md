# DesafioControleFluxo

Este é um projeto que implementa um contador que recebe dois parâmetros e realiza uma contagem de números incrementados.

## Descrição

O sistema recebe dois números inteiros como parâmetros via terminal. Com estes dois números, a aplicação realiza um loop (`for`) e imprime os números incrementados no console. Se o primeiro parâmetro for maior que o segundo, uma exceção personalizada chamada `ParametrosInvalidosException` é lançada.

## Estrutura do Projeto

- **Contador.java**: Classe principal que contém o método `main` e a lógica de contagem.
- **ParametrosInvalidosException.java**: Classe que representa a exceção personalizada.



## Exemplo de Uso

```sh
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
///////////////////////////////////
Digite o primeiro parâmetro
30
Digite o segundo parâmetro
3
O segundo parâmetro deve ser maior que o primeiro
