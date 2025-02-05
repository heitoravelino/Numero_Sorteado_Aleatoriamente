Jogo do Número Secreto

Este é um simples jogo de adivinhação onde o jogador tenta descobrir um número secreto gerado aleatoriamente. O objetivo é adivinhar o número correto com o menor número de tentativas possível.

Como o Jogo Funciona:

Início do Jogo:

Um alerta é exibido para dar boas-vindas ao jogador: Boas vindas ao jogo do número secreto.

O número secreto é gerado aleatoriamente entre 1 e um valor máximo (neste caso, 100).

Interação do Jogador:

O jogador é solicitado a adivinhar o número secreto digitando um valor entre 1 e o valor máximo.

Se o chute do jogador não for igual ao número secreto, uma dica é dada:

O número secreto é menor que ... se o chute for maior.

O número secreto é maior que ... se o chute for menor.

O número de tentativas é contado.

Fim do Jogo:

Quando o jogador acerta o número, uma mensagem é exibida indicando o sucesso e o número de tentativas usadas: Isso ai! Você descobriu o número secreto ... com ... tentativas.

Estrutura do Código:

let numeroMaximo = 100;: Define o valor máximo para o número secreto.

let numeroSecreto = parseInt(Math.random() * numeroMaximo + 1);: Gera o número secreto aleatório.

Loop while: Continua solicitando chutes ao jogador até que o número correto seja adivinhado.

Incrementação de Tentativas: Conta cada tentativa do jogador.

Condicional if-else: Fornece feedback ao jogador se o chute é maior ou menor que o número secreto.

Mensagem Final: Informa o jogador sobre o sucesso e o número de tentativas realizadas.

Observações:

O código utiliza prompt e alert para interações simples com o usuário.

A função Math.random() é usada para gerar o número secreto aleatoriamente.

A declaração condicional if-else fornece feedback dinâmico ao jogador para melhorar a experiência do jogo.
