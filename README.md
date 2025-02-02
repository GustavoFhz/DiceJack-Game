# DiceJack

DiceJack é um jogo simples de azar implementado em Java. O jogador escolhe três números entre 1 e 6, e o programa gera três valores aleatórios simulando o lançamento de dados. O objetivo do jogo é que a soma dos números escolhidos seja maior do que a soma dos valores sorteados, mas com uma diferença máxima de 2 pontos.

## Regras do Jogo
1. O jogador escolhe três números entre 1 e 6.
2. O programa gera três números aleatórios entre 1 e 6.
3. A soma dos números escolhidos pelo jogador é comparada com a soma dos números sorteados.
4. O jogador ganha se sua soma for maior que a dos dados, mas com uma diferença menor que 3 pontos.

## Como Executar o Projeto

1. Certifique-se de ter o Java instalado em seu sistema.
2. Baixe ou clone este repositório.
3. Compile o arquivo `DiceJack.java`:
   ```sh
   javac DiceJack.java
   ```
4. Execute o programa:
   ```sh
   java DiceJack
   ```
5. Siga as instruções exibidas no terminal para jogar.

## Estrutura do Código
O código é composto por:
- Um método `main`, que gerencia a interação do jogador.
- O método `rollDice()`, que simula o lançamento de um dado.
- O método `userWon()`, que verifica se o jogador venceu.
- Os métodos `isLessThan1()` e `isHigherThan6()`, que garantem que os números inseridos estão dentro do intervalo permitido.

## Exemplo de Saída
```sh
Enter three numbers between 1 and 6:
3 4 5
Your sum 12 Dice sum 10
Congratulations, you won!
```

## Melhorias Futuras
- Permitir múltiplas rodadas sem precisar reiniciar o jogo.
- Implementar uma interface gráfica.
- Adicionar a possibilidade de jogar contra outro jogador.

## Licença
Este projeto é de uso livre para estudos e melhorias.

