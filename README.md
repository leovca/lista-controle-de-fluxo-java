# Atividade: Controle de Fluxo

## Orientações

- Cada uma das questões deve ser entregue dentro de um pacote.
  Exemplo: "questao01","questao02",...,"questaoXX".

- Dentro de cada pacote deve ter uma classe chamada Principal que deverá ter o método main.

# Atividades

1. Escreva um programa que receba dois inteiros e informe qual o maior deles. Ex:

   ```text
    Digite o primeiro número: 10
    Digite o segundo número: 20
    > O maior número é 20
   ```

2. Escreva um programa que solicite ao usuário o seu peso e altura, calcule e imprima seu IMC e sua classificação.

```

| IMC         | Classificação                |
| ----------- | ---------------------------- |
| < 18,5      | Magreza                      |
| 18,5 - 24,9 | Saudável                     |
| 25,0 - 29,9 | Sobrepeso                    |
| 30,0 - 34,9 | Obesidade Grau I             |
| 35,0 - 39,9 | Obesidade Grau II (Severa)   |
| >= 40       | Obesidade Grau III (mórbida) |

```

A fórmula do IMC é: **IMC** = peso / altura²

Ex:

```text
  Digite seu peso: 80
  Digite sua altura: 1.80
  > Seu IMC é 24.69 e você está Saudável
```

3. Escreva um programa que receba um número e informe se o número é par ou ímpar. Ex:

   ```text
     Digite um número: 10
     > O número 10 é par
   ```

4. Escreva um programa que verifique a validade de uma senha fornecida pelo usuário. A senha válida é o número 1234. Devem ser impressas as seguintes mensagens:

|                  |                             |
| ---------------- | --------------------------- |
| ACESSO PERMITIDO | caso a senha seja válida.   |
| ACESSO NEGADO    | caso a senha seja inválida. |

Ex:

```text
  Digite a senha: 1234
  > ACESSO PERMITIDO
```

```text
  Digite a senha: 9999
  > ACESSO NEGADO
```

6. As laranjas custam R$0,50 cada se forem compradas menos do que uma dúzia, e R$0,30 se forem compradas pelo menos doze. Escreva um programa que leia o número de laranjas compradas, calcule e escreva o valor total da compra.

7. Escreva um programa que receba três inteiros e informe qual o menor deles.

8. Escreva um programa que leia as medidas dos lados de um triângulo e escreva se ele é equilátero, isósceles ou escaleno.
   O comprimento de cada lado de um triangulo é menor do que a soma dos outros dois
   lados.

   - Chama-se equilátero o triangulo que tem três lados iguais.
   - Denominam-se isósceles o triangulo que tem o comprimento de dois lados iguais.
   - Recebe o nome de escaleno o triangulo que tem os três lados diferentes.

9. Escrever um programa para exibir os números de 1 até 50 na tela usando o **for**.

10. Escrever um programa para exibir os números de 1 até 50 na tela usando o **while**.

11. Escrever um programa para exibir os números de 1 até 50 na tela usando o **do..while**.

12. Construa um programa que solicite do usuário um número inteiro e positovo e imprima todos os números pares entre 0 e o número digitado.

13. Construa um programa que solicite infinitos números inteiros ao usuário. Ao receber o valor “**0**”, o programa deve imprimir a quantidade de números pares que foram digitados e a média de todos os números digitados, exceto o “**0**”.

14. Construa um programa que exiba um menu com 4 opções:

<img src="https://user-images.githubusercontent.com/5587998/179874116-f479efe9-06c0-4982-bbd5-8bc23610a87e.png" min-width="100px" max-width="100px" width="100px" align="right" alt="Calculadora">

<p align="left">

```

1 - Somar
2 – Subtrair
3 - Multiplicar
4 – Dividir
5 - Sair

```

Ao escolher uma das opções entre 1 e 4 o programa deve solicitar que o usuário informe dois números, calcular a operação escolhida, imprimir o resultado e apresentar o menu novamente. Ao selecionar a opção 5 o programa deve ser finalizado. Escolhendo uma opção que não existe no menu, o programa deve apresentar o menu novamente.

</p>

15. Uma pizzaria fornece 10% de desconto para funcionários e 5% de desconto para clientes vips. Faça um programa que calcule o valor total a ser pago pela venda de uma pizza. O programa deverá ler o valor da compra e um código que indica o tipo de cliente: 1-Comum, 2-Vip e 3-Funcionário.

16. Escreva um programa utilizando o comando switch que imprima um mês de acordo com o número digitado pelo usuário. (1 – Janeiro,...,12 – Dezembro).

  <img src="https://user-images.githubusercontent.com/5587998/179875074-7fe74eb1-8196-4974-8e97-80a9507e0a7a.png" min-width="100px" max-width="100px" width="100px" align="right" alt="Calculadora">

17. Construa um programa que imprima a Tabuada da divisão e multiplicação de um determinando inteiro informado pelo usuário. A tabuada deve apresentar das operações e os resultados entre o número e os números do intervalo entre 1 e 10.

18. O fatorial de um número n (n pertence ao conjunto dos números naturais) é sempre o produto de todos os seus antecessores, incluindo si próprio e excluindo o zero. Exemplo de número fatorial: 6! = 6 x 5 x 4 x 3 x 2 x 1 = 720. Construa um programa que solicite do usuário um número e imprima o seu fatorial.

19. Escreva um programa que, dados dois números inteiros positivos inseridos pelo usuário, verifique e imprima a quantidade de números primos entre eles.

20. Usando switch, escreva um programa que leia um inteiro entre 1 e 7 e imprima o dia da semana correspondente a este número. Isto e, domingo se 1, segunda-feira se 2, e assim por diante.

21. Faça um programa para verificar se um determinado número inteiro e divisível por 3 ou 5, mas não simultaneamente pelos dois.

22. Leia a idade e o tempo de serviço de um trabalhador e escreva se ele pode ou não se aposentar. As condições para aposentadoria são:

    - Ter pelo menos 65 anos,
    - Ou ter trabalhado pelo menos 30 anos,
    - Ou ter pelo menos 60 anos e trabalhado pelo menos 25 anos.

23. Usando switch, escreva um programa que leia um inteiro entre 1 e 12 e imprima o mês correspondente a este número. Isto e, janeiro se 1, fevereiro se 2, e assim por diante.
