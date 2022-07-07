# Projeto Jogo de Xadrez ♟️
Esse é o primeiro grande projeto proposto no curso de Programador Java da DevSuperior, criei ele para treinar tudo que aprendi no curso.

A tecnologia usada foi Java Poo, e usei vários módulos e ferramentas que essa linguagem maravilhosa proporciona. <br>
Segue abaixo uma lista de funções de Java Poo que foram utilizadas nesse projeto.

<li>Construtorers</li>
<li>Sobercarga</li>
<li>Encapsulamento</li>
<li>Arrays</li>
<li>Listas</li>
<li>Enumeração</li>
<li>Composição</li>
<li>Herança</li>
<li>Polimorfismo</li>
<li>Tratamento de exceção</li>


# Modelo relacional do projeto


A principio podemos ver que o modelo ele é dividido em duas partes, a parte de tabuleiro e a parte de xadrez. A camada tabuleiro é formada por tabuleiro(board) e peças(piece), podemos também ver as classes auxiliares que ficam dentro do retangulo que são: posição(Position) e a exceção personalizada(BoardException), assim completa a camada tabuleiro. A camada de Xadrex é composta por pequenos espaços denominados: Rei(King), Bispo(Bishop), Cavalo(Knight), Peão(Pawn), Rainha(Queen) e Torre(Rook), podemos ver também as classes que são as responsáveis pelas peças e sua movimentação: Partida Xadrez(ChessMatch) e Peça Xadrez(ChessPiece), essa parte ficou responsável pela inteligencia do jogo.


![Captura de tela 2022-07-07 154856](https://user-images.githubusercontent.com/94095714/177850239-9b9f658e-f5cf-4821-943e-deafbf7fc6d5.png)
![Captura de tela 2022-07-07 155558](https://user-images.githubusercontent.com/94095714/177850893-9a64b4bd-fc1e-4fd7-83a8-01e855850074.png)

# Tabuleiro

O tabuleiro foi projetado para que fosse feito jogadas mais facilitadas, as jogadas são feitas colocando a letra e o número de onde a peça de encontra, o tabuleiro é baseado no tabuleiro habitual: <br>

<h2> Tabuleiro Original <br>

![Captura de tela 2022-07-07 160121](https://user-images.githubusercontent.com/94095714/177851956-bd61be1d-c106-4d25-bff8-43c031c03a00.png)
![Captura de tela 2022-07-07 160144](https://user-images.githubusercontent.com/94095714/177851967-1b9ee0a8-01a8-4d69-bcb4-e51da57fea97.png)

<h2> Resultado em Console <br>

![Captura de tela 2022-07-07 155948](https://user-images.githubusercontent.com/94095714/177852081-6aa4aea4-1390-426e-a7fd-ff42e0d7b3a8.png)
![Captura de tela 2022-07-07 160426](https://user-images.githubusercontent.com/94095714/177852255-e93fbb86-c737-4bae-808d-ef002c23ca0d.png)


# Como jogar

Para jogar é só baixar o arquivo .zip aqui no GitHub e para executar ele é necessário abrir a pasta >bin<, botão direito dentro dela e depois executar no Git Bash usando o comando: <br>

<h3> java application/Program </h3><br>

Com isso ele roda em seu terminal e depois é só se divertir jogando. :D






