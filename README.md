Este projeto consiste em um programa em Java que permite aos usuários realizar três tipos diferentes de apostas: apostar em um número de 0 a 100, apostar em uma letra de A à Z e apostar se um número é par ou ímpar. O programa utiliza a entrada do teclado para coletar as apostas dos usuários e gera resultados com base nas regras estabelecidas.

Funcionalidades Implementadas:

1- Aposta de 0 a 100:
O usuário insere um número inteiro de 0 a 100;
Se o número estiver fora do intervalo permitido, o programa exibe "Aposta inválida";
Um número aleatório dentro do intervalo de 0 a 100 é gerado;
Se o número apostado pelo usuário coincidir com o número sorteado, o programa exibe "Você ganhou R$ 1.000,00 reais"; caso contrário, exibe "Que pena! O número sorteado foi: X";
2- Aposta de A à Z:
O usuário insere uma letra de A à Z, que pode ser maiúscula ou minúscula;
Se a entrada não for uma letra, o programa exibe "Aposta inválida";
A entrada do usuário é convertida para maiúscula;
Uma letra premiada é escolhida, correspondente à inicial do nome do desenvolvedor;
Se a letra apostada coincidir com a letra premiada, o programa exibe "Você ganhou R$ 500,00 reais"; caso contrário, exibe "Que pena! A letra sorteada foi: X";
3- Aposta de número par ou ímpar:
O usuário insere um número inteiro;
O programa verifica se o número é par ou ímpar usando o operador de módulo (%);
Se o número for par, o programa exibe "Você ganhou R$ 100,00 reais"; se for ímpar, exibe "Que pena! O número digitado é ímpar e a premiação foi para números pares";

Implementação:

O programa foi desenvolvido em Java, utilizando as bibliotecas Scanner e Random para entrada de dados do usuário e geração de números aleatórios, respectivamente. O método System.in.read() foi utilizado para ler caracteres do teclado. As regras de cada tipo de aposta foram implementadas com estruturas de decisão condicional (if-else) para comparar as entradas do usuário com os resultados gerados pelo sistema.






