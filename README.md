# hipotese de Collatz

Em 1937, um matemático alemão chamado Lothar Collatz formulou uma hipótese intrigante (ainda não comprovada) que pode ser descrita da seguinte forma:

- Pegue qualquer número inteiro diferente de zero e nomeie-o como c0;
- Se for par, avalie um novo c0 como c0 ÷ 2;
- Caso contrário, se for ímpar, avalie um novo c0 como 3 × c0 + 1;
- Se c0 ≠ 1 , volte ao ponto 2.

A hipótese diz que, independentemente do valor inicial de c0, ela sempre vai para 1.


Este programa que lê um número natural e executa as etapas acima, desde que c0 permaneça diferente de 1.
