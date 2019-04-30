# Análise de Algoritmos

Utilize os seus conhecimentos sobre análise de algoritmos para resolver as questões abaixo.

#### 1 Problema
##### Quais são as duas características mais comuns para analisar algoritmos?	
R: Tempo e consumo de memória, respectivamente Complexidade de Tempo e de espaço.

#### 2 Problema
##### Por que a medida de tempo em segundos não representa qualificadamente o tempo de execução de um algoritmo?
R:  Porque existem vários fatores que modificam o tempo de execução, então a medida de segundos não é melhor opção, e sim a feita através de quantidade de passos que o algoritmo precisa para finalizar sua execução.

#### 3 Problema
##### A medida de tempo de um algoritmo é realizada através de qual informação? O que pode afetá-la?
R: A medição de tempo é feita através da quantidade de passos que o algoritmo precisa para finalizar sua execução. O tempo de execução de um algoritmo ou método da estrutura de dados é afetado pelo ambiente de hardware (compilador, processador, Sistema operacional linguagem de programação e etc.) e tamanho da entrada.

#### 4 Problema
##### Na análise de algoritmos, qual é o valor da base da função logarítmica e exponencial? Por que é escolhido este valor?
R: A base é 2, e é escolhida porque análise de algoritmos trabalha com números binários, ou seja, 2 valores. 

#### 5 Problema
##### O que é complexidade de tempo?
R: O tempo de execução ou complexidade de tempo de M é a função f: N → N, onde f(n) é o número máximo de passos que M usa sobre entradas de comprimento n. É um costume generalizado usar n para representar o comprimento da entrada.

#### 6 Problema
##### Dado dois algoritmos A e B com as complexidades de tempo respectivamente f1 e f2, qual é o melhor algoritmo? O que indica qual é o melhor algoritmo?
R: O algoritmo que tiver a função com o menor valor representa uma solução melhor, ou seja, o algoritmo precisa de menos tempo ou passos para resolver o determinado problema. Oque indica o melhor algoritmo é a taxa de crescimento.

#### 7 Problema
##### Em uma função de complexidade, o que representa o termo n?
R: O n representa o tamanho da entrada.

#### 8 Problema
##### Quais são as operações primitivas de um algoritmo?
R: Atribuição de valores a variáveis, Chamadas de métodos, Operações aritméticas (por exemplo, adição de dois números), Comparação de dois números, Acesso a um arranjo, Seguimento de uma referência para um objeto e Retorno de um método.

#### 9 Problema
##### Qual é o valor de uma operação primitiva de um algoritmo?
R: Para cada operação primitiva se atribui o valor 1.

#### 10 Problema
##### Desenvolva o pseudocódigo do algoritmo SOMA, que realiza a soma de dois números inteiros recebidos por parâmetro e tem como saída a resultado da operação. Identifique a sua função de complexidade de tempo.
![Capturar](https://user-images.githubusercontent.com/36802539/56842931-079f8a00-6871-11e9-915f-64f22654a276.JPG)

#### 11 Problema
##### Desenvolva o pseudocódigo do algoritmo SOMA V ET OR, que realiza a soma de todos os elementos de um vetor. O algoritmo recebe o vetor V e tem como saída o resultado. Identifique a sua função de complexidade de tempo.
![Capturar2](https://user-images.githubusercontent.com/36802539/56842950-47ff0800-6871-11e9-9e04-9b0dbadedb31.JPG)

#### 12 Problema
##### Desenvolva o pseudocódigo do algoritmo CONTAGEM ÍMPARES, que realiza a contagem de números impares de um vetor. O algoritmo recebe o vetor V e tem como saída o resultado. Identifique a sua função de complexidade de tempo.
![Capturar3](https://user-images.githubusercontent.com/36802539/56842958-6a912100-6871-11e9-9bce-c85b9cac8ca2.JPG)

#### 13 Problema
##### Desenvolva o pseudocódigo do algoritmo SOMA MATRIZ, que realiza a soma de todos os elementos de uma matriz. O algoritmo recebe a matriz M e tem como saída o resultado. Identifique a sua função de complexidade de tempo.
![Capturar4](https://user-images.githubusercontent.com/36802539/56842960-84326880-6871-11e9-9d3c-cbe93d82487a.JPG)

#### 14 Problema
##### Desenvolva o pseudocódigo do algoritmo BUSCA MATRIZ, que identifica posição x e y de um elemento em uma matriz. O algoritmo recebe a matriz M e o valor V e tem como saída a posição x e y. Identifique a sua função de complexidade de tempo.
![Capturar](https://user-images.githubusercontent.com/36802539/56933403-0adb8580-6abe-11e9-9971-bc0105a9d94d.JPG)

#### 15 Problema
##### O que é análise assintótica? Qual é o seu objetivo?
R: O tempo exato de um algoritmo é frequentemente uma expressão complexa. Tanto para identificar como para calcular. Portanto, apenas se utiliza uma estimativa, chamada de análise assintótica, com objetivo de compreender o tempo de execução para entradas grandes. Ou seja, é um método de descrever o comportamento de limites.

#### 16 Problema
##### Qual é o processo da análise assintótica? Crie um exemplo.
![Capturar6](https://user-images.githubusercontent.com/36802539/56842996-fdca5680-6871-11e9-9006-1c845f2f695c.JPG)

#### 17 Problema
##### O que é a notação assintótica?
R: É uma notação para descrever uma fórmula matemática que se importa apenas com o maior componente da fórmula e ignora os fatores menores ou constantes.

#### 18 Problema
##### O que é a notação O-Grande ou Big-Oh?
R: Notação O –grande diz que uma função é menor que ou igual a outra função g(n). x Ou seja, f é limitada superiormente por g (até no máximo um fator constante) assintoticamente.

#### 19 Problema
##### Qual é a definição formal da notação O-Grande?
R: Sejam f e g funções f, g: N → R+. Digamos que f(n) = O(g(n)) se existem inteiros positivos c e n0 tais que para todo inteiro n ≥ n0 
   
   #### f(n) ≤ cg(n).

Quando f(n) = O(g(n)) dizemos que g(n) é o limite superior para f(n) ou, mais precisamente, que g(n) é um limitante assintótico para f(n), para enfatizar que estamos suprimento fatores constantes.

#### 20 Problema
##### Crie um gráfico explicando a notação O-grande. Utilize f(n) = 2n + 4. Qual é um valor possível para n0?
![Capturar](https://user-images.githubusercontent.com/36802539/56843482-d24a6a80-6877-11e9-826a-fce969a3dfb5.JPG)

#### 21 Problema
##### O que é a notação o-pequeno ou Little-Oh?
R: Notação O –pequeno diz que uma função é menor que a outra função g(n). Ou seja, f é dominada por g assintoticamente.

#### 22 Problema
##### Qual é a definição formal da notação o-pequeno?
R:Sejam f e g funções f, g: N → R+. Digamos que f(n) = o(g(n)) se

![image](https://user-images.githubusercontent.com/36802539/56843062-a11b6b80-6872-11e9-8bc8-01e68b64bd7d.png)
                            
Em outras palavras, f(n) = O(g(n)) significa que, para qualquer número real c > 0, existe um número n0, onde f(n) < cg(n) para todo n ≥ n0.

#### 23 Problema
##### Crie um gráfico explicando a notação o-pequeno.
![Capturar2](https://user-images.githubusercontent.com/36802539/56843483-d37b9780-6877-11e9-925a-3b8d80856582.JPG)

#### 24 Problema
##### Passe a notação O-grande e o-pequeno as funções abaixo:
##### A) F(n) = n + 1

O(n)

o(n²)
 
##### B) F(n) = 8

O(1)

o(n)
 
##### C) F(n) = 2n² − 1

O(n²)

o(2^n)
 
##### D) F(n) = nlogn

O(logn)

o(n²)
 
##### E) F(n) = 3n! + 2n

O(n!)

o(n!²)
 
##### F) F(n) = 3n³ + 2n² + 4n + 6

O(n³)

o(n!)
 
##### G) F(n) = 5^n + 11

O(5^n)

o(n * n!)
 
##### H) F(n) = 3logn

O(logn)

o(n²)

#### 25 Problema
##### Identifique o O-Grande dos algoritmos desenvolvidos nos Problemas 10 até 14.
R:
##### 10) f(n)=2
O(1)
o(n)
 
##### 11) f(n)=3n+3
O(m)
o(nlog(n))
 
##### 12) f(n)=3n+4
O(n)
o(n²)
 
##### 13) f(n)=3n² + 2n + 4
O(n²)
o(n!)
 
##### 14) f(n)=3n² + 2n + 5
O(n²)
o(2^n)







