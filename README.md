#Lab2 CS50 Harvard Week2 

# Scrabble Game

Este é um programa em C que implementa um jogo curto de Scrabble, onde dois jogadores inserem suas palavras e o jogador com a maior pontuação vence.

## Pontuação das letras

As pontuações das letras são armazenadas no array `POINTS`, onde cada índice representa uma letra do alfabeto. Por exemplo, `POINTS[0]` representa a pontuação da letra 'A' e `POINTS[25]` representa a pontuação da letra 'Z'.

## Funções

O programa possui duas funções principais:

1. `compute_score(string word)`: Calcula a pontuação de uma palavra fornecida como entrada. Os caracteres que não são letras recebem zero pontos, e letras maiúsculas e minúsculas recebem os mesmos valores de pontos. A função retorna a pontuação calculada.

2. `main()`: Função de entrada do programa. Solicita que os dois jogadores insiram suas palavras usando a função `get_string()`, chama `compute_score()` para calcular as pontuações correspondentes e imprime o vencedor ou empate.

## Como usar

1. Compile o código usando um compilador C compatível.
