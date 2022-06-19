### Estruturas condicionais e operadores :mega:



Voltando ao exemplo anterior:

**Exemplo de estrutura de algoritmo:**

Início programa:

`Nota1: 5        **< Variável**`

`Nota = 8`

`Resultado = 0`

`Resultado = (Nota1+ Nota2)/2   **< Constante**`   

`Escreva resultado`

`Fim programa`

`Saída: 6,5`

Como colocar algum tipo de verificação se o aluno foi aprovado ou não?

Utilizaremos a **ESTRUTURA CONDICIONAL.**

**Condição** seria que dado o estado de uma pessoa ou uma coisa existe uma condição pra isso acontecer. O **Condicional,** expressa uma condição ou uma suposição ou hipótese.

A ideia de uma estrutura condicional é que dado uma condição satisfeita eu executo determinada tarefa ou operação. Caso seja inverdade a condição acarreta em uma exceção.

Existem diferentes estruturas condicionais, onde a "simples" verifica se a condição foi satisfeita e executa a operação, na "composta" ela verifica se a condição foi satisfeita, se não joga uma exceção, e a encadeada ocorre o "se", "senão" um dentro do outro.

![](C:\Users\pp\Desktop\1.PNG)



Os operadores relacionados são:

![](C:\Users\pp\Desktop\Capturar.PNG)

Todos estes são utilizados numa estrutura condicional para que possam verificar tal afirmação e se for verdadeira executa a ação.

**Ex de condição simples:** `Se(<condição>) então`

​                              `<instruções para condição verdadeira>`

​                           `fim_se`

**Ex de condição composta:** `Se (<condição>) então`

​                                 `<instruções para condição verdadeira>`

​                             `Senão`

​                                 `<instruções para condiçãofalsa>`

​                              `fim_se`

**Ex de condição encadeado:** `Se (<condição 1>) então`

​                                 `<instruções para condição verdadeira>`

​                             `Senão`

​                                `Se (<condição 2>) então`

​                           `<instruções para condição 2 verdadeira e condição 1 falsa>`

​                             `Senão`

​                           `<instruções para condição 1 e 2 falsas>`

​                              `fim_se`

**Operadores lógicos:** Utilizados para resposta simplificada como verificação de verdadeiro ou falso. Temos o AND, OR e NOT.

O AND ou "E", é sempre falso quando um ou outro e verdadeiro quando os dois são satisfeitos. Está relacionado a Interseção. Ex: Curso de inglês.

​                `se(gramatica . e .conversação) então`     

​                     `escreva "aprovado"`

​                  `senão`

​                     `escreva "Reprovado"`

Temos o "OR ou" OU" onde se uma das condições é verdadeira encaminho verdadeiro a menos que as duas sejam falsas. Está associado a União.

   Ex:           `se(choveu .ou. grama_molhada) então`     

​                     `escreva "Plantas regadas"`

​                  `senão`

​                     `escreva "Regar plantas"`

Temos o NOT, operação de negação onde ocorre a inversão do resultado lógico. Se o resultado seria verdadeiro se torna falso, se era falso se torna verdadeiro.

Também pode ser utilizado da seguinte forma Ex: Not B- > tudo que não está em B ou seja tudo que está em A e não pertence a B.