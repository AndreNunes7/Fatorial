# Cálculo do Fatorial

Este é um programa em C# que calcula o fatorial de um número inteiro inserido pelo usuário.

## Funcionamento

O fatorial de um número inteiro positivo `n` é o produto de todos os inteiros positivos menores ou iguais a `n`. Por exemplo, o fatorial de 5 é 5 * 4 * 3 * 2 * 1 = 120.

O programa começa pedindo ao usuário para inserir um número inteiro. Em seguida, ele utiliza um laço `while` para calcular o fatorial desse número. A cada iteração, o programa multiplica a variável `f` (inicializada como 1) pelo valor atual de `num` e decrementa `num` em 1. Isso continua até que `num` seja menor ou igual a 1. No final, o programa exibe o resultado do cálculo do fatorial.

## Como usar

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.

2. Copie o código fornecido e cole-o em um arquivo `.cs`.

3. Compile e execute o programa.

4. O programa pedirá para você inserir um número inteiro positivo. Insira um número inteiro positivo e pressione Enter.

5. O programa exibirá o resultado do cálculo do fatorial do número inserido.

## Observações

- Este código é um exemplo simples de como calcular o fatorial de um número em C#. Ele não lida com entradas inválidas ou valores negativos, portanto, certifique-se de inserir um número inteiro positivo.

- Lembre-se de que o fatorial de números grandes pode crescer rapidamente, resultando em valores muito grandes. O código pode não lidar bem com números extremamente grandes devido a limitações de representação numérica em computadores.
