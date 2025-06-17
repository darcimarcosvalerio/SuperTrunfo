# Super Trunfo em Java

Este repositório contém a implementação do jogo Super Trunfo em Java para o desafio da disciplina de [Nome da Disciplina].

## Como Compilar e Rodar

1. Certifique-se de ter o Java Development Kit (JDK) instalado.
2. Baixe ou clone este repositório.
3. Abra um terminal na pasta raiz do projeto.
4. Compile os arquivos Java:
   ```bash
   javac Carta.java Baralho.java Jogador.java Jogo.java
   ```
5. Execute o jogo:
   ```bash
   java Jogo
   ```

## Estrutura do Projeto

* `Carta.java`: Define as propriedades e o comportamento de uma carta.
* `Baralho.java`: Gerencia a coleção de cartas, embaralha e distribui.
* `Jogador.java`: Representa um jogador e sua mão de cartas.
* `Jogo.java`: Contém a lógica principal do jogo, orquestrando as rodadas.

## Regras do Jogo

* Cada jogador recebe um número igual de cartas.
* O primeiro jogador escolhe um atributo da sua carta do topo.
* Todos os jogadores revelam a carta do topo e o valor do atributo escolhido.
* A carta com o maior valor no atributo escolhido vence a rodada (você pode definir regras para peso, onde o menor ganha).
* O vencedor da rodada pega todas as cartas jogadas e as coloca no final da sua mão.
* Em caso de empate, as cartas da rodada vão para um "pote", e o vencedor da próxima rodada leva o pote junto.
* O jogo continua até que um jogador tenha todas as cartas.

## Contribuições

Sinta-se à vontade para sugerir melhorias ou reportar problemas!
