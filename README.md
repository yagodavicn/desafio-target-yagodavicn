# EXPLICAÇÃO DE CADA DESAFIO

## DESAFIO 1 
Inicializei as variáveis INDICE, SOMA e K com seus respectivos valores e o laço while repete enquanto K for menor que INDICE. A cada repetição, incremento K em 1 e somamos o valor de K à variável SOMA. No final do laço, o valor de SOMA será a soma de todos os números de 1 a 13. O valor final de SOMA é 91.

## DESAFIO 2
A função pertence_fibonacci começa com os dois primeiros números da sequência de Fibonacci (0 e 1), aproveitei para usar um laço while que continua somando os dois últimos números da sequência até que o valor de b (o segundo número) seja maior ou igual ao número fornecido. Se o número for igual a b, ou se o número for 0, então ele pertence à sequência de Fibonacci. Caso contrário, não pertence, e com isso o programa pede um número, verifica se ele pertence à sequência, e imprime a mensagem correspondente.

## DESAFIO 3
Primeiramente, registro todos os dias com seus faturamentos, e depois removo os dias sem faturamento (dias em que o valor é 0.0). Utilizei as funções min() e max() para encontrar o menor e maior valor de faturamento ; A média de faturamento é calculada somando os valores válidos e dividindo pelo número de dias com faturamento, e finalmente, contamos quantos dias tiveram faturamento acima da média usando uma lista de compreensão. O programa imprime o menor, maior valor e a quantidade de dias com faturamento acima da média.

## DESAFIO 4
Criei um dicionário com os valores de faturamento de cada estado, e calculei o faturamento total somando os valores. Para cada estado, calculei o percentual de representação dividindo o valor de faturamento daquele estado pelo faturamento total e multiplicando por 100. O programa imprime o percentual de cada estado.

## DESAFIO 5
O programa pede ao usuário uma string como entrada para ser invertida ; Coloco uma variável vazia (string_invertida) para armazenar o resultado; Percorre-se a string de trás para frente utilizando um laço FOR que começa no último caractere (índice len(string) - 1) e termina no primeiro sendo que cada caractere é adicionado à variável string_invertida, formando a string invertida. Por fim, o programa imprime a string invertida.