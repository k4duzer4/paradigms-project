# README do Tic-Tac-Color

## Visão Geral

Tic-Tac-Color é um jogo em Java baseado em console onde os jogadores se revezam colocando cartas coloridas em um tabuleiro 3x3 para formar sequências de sua cor na horizontal, vertical ou diagonal. Este README fornece uma visão geral do projeto, incluindo suas classes, métodos e como jogar.

## Classes

### 1. Tabuleiro

A classe `Tabuleiro` representa o tabuleiro do jogo, que é uma grade 3x3 onde os jogadores colocam suas cartas. Contém métodos para adicionar cartas ao tabuleiro, verificar vencedores e imprimir o estado atual do tabuleiro.

### 2. Carta

A classe `Carta` representa uma carta de jogo com quatro valores (cima, baixo, esquerda, direita) e uma cor. Cada carta pode ser colocada no tabuleiro e influencia as cartas vizinhas com base em seus valores.

### 3. Jogador

A classe `Jogador` representa um jogador no jogo. Cada jogador tem um nome, uma cor e um conjunto de cartas para jogar. Os jogadores se revezam colocando cartas no tabuleiro.

### 4. Principal

A classe `Principal` contém o método principal e serve como ponto de entrada para o jogo. Ela inicializa os jogadores, o tabuleiro e orquestra o loop de jogo até que um vencedor seja determinado.

## Como Jogar

1. Execute a classe `Principal` para iniciar o jogo.
2. Os jogadores se revezam colocando cartas no tabuleiro.
3. Cada jogador seleciona uma carta de sua mão e escolhe uma posição no tabuleiro para colocá-la.
4. O jogo verifica sequências da mesma cor na horizontal, vertical ou diagonal.
5. O jogo termina quando um jogador forma uma sequência da sua cor ou o tabuleiro fica cheio sem um vencedor.

## Contribuições

Contribuições para melhorar o jogo, adicionar recursos ou corrigir bugs são bem-vindas. Sinta-se à vontade para fazer um fork do repositório e enviar pull requests com suas alterações.


