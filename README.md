### Projeto

Este projeto foi desenvolvido durante o bootcamp da DIO, utilizando Java. O objetivo foi criar um desafio de projeto para explorar alguns cenários com fluxos condicionais, laços de repetição e tratamento de exceções. No final, implementamos um pequeno sistema contador para exercitar todo o conteúdo ministrado nas aulas.

#### Desafio de Controle de Fluxo

Vamos aplicar todo o conteúdo apresentado no módulo de Controle de Fluxo codificando o seguinte cenário:

O sistema deve receber dois parâmetros via terminal, representando dois números inteiros. Com esses dois números, você deve determinar a quantidade de iterações (usando um laço `for`) e imprimir no console (`System.out.print`) os números incrementados. Por exemplo:

Se você passar os números 12 e 30, teremos 18 iterações para imprimir os números, resultando em: "Imprimindo o número 1", "Imprimindo o número 2", e assim por diante.

Caso o primeiro parâmetro seja MAIOR que o segundo, você deve lançar uma exceção personalizada chamada `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

Crie o projeto `DesafioControleFluxo`. Dentro do projeto, crie a classe `Contador.java` para realizar toda a codificação do nosso programa. Além disso, crie a classe `ParametrosInvalidosException`, que representará a exceção de negócio no sistema.
