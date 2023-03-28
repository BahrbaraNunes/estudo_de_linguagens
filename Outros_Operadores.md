<a href="README.md" target="_self"  rel="prev">Voltar á Página Inicial.</a>

## Operadores Lógicos
<code><pre>
#Tabela verdade do AND:
#Só será verdadeiro se ambos forem verdadeiros.
True and True
True and False
False and True
False and False

#Tabela verdade do OR:
#Basta apenas uma condição ser verdadeira para ser verdadeiro.
True or True
True or False
False or True
False or False

#Tabela verdade do XOR:
#Para ser verdadeiro tem ser um ou outro.
True != True
True != False
False != True
False != False

#Operador de Negação (unário):
#Basta acrescentar o 'not' na frente.
not True
not False
#A negação dupla voltará para o valor original:
not not True
</pre></code>

### Outros Operadores

<p>Exemplo de operadores ternários:</p>
<code><pre>
esta_chovendo = True

print('Hoje estou com as roupas ' + ('molhadas.' if esta_chovendo else 'secas.'))
</pre></code>

<p>Exemplo de operador membro:</p>
<code><pre>
lista = [1, 2, 3, 'Ana', 'Bruce']
2 in lista # 2 está na lista, verdadeiro.
'Ana' not in lista # Ana não está na lista, será falso, pois ela está na lista.
</pre></code>

<p>Operador de Identidade:</p>
<code><pre>
x = 3
y = x 
z = 3

x is y # Vai dar verdadeiro, pois eles tem o mesmo valor, logo x é y 
y is z
x is not z # Vai dar falso, pois pois x tem o mesmo valor que z, logo  x é z 

lista_a = [1, 2, 3]
lista_b = lista_a
lista_c = [1, 2, 3]

lista_a is lista_b # Verdadeiro
lista_b is lista_c # Falso
lista_a is not lista_c # Verdadeiro
#A lista 'a' e 'b' estão ocupando o mesmo espaço de memoria, já a lista 'c' ele ocupa outro espaço.
</pre></code>

<h2>Estruturas Condicionais</h2>

<h4>Else em Python</h4>
<p>O ELSE surge depois do IF, em complemento lógico a ele. Então, não existe hipótese de escrever um ELSE sem um IF antes. Geralmente, o ELSE não requer um teste, uma comparação, pois ele executa algo caso a comparação do IF não passe. Portanto, você só precisa declarar o ELSE e adicionar o bloco de comandos. </p>

<h4>IF em Python</h4>
<p>Já o IF deve propor alguma coisa. É preciso escrever o IF e logo depois colocar a condição analisada. Então, em seguida, o bloco de comandos. </p>

<h4>Elif em Python</h4>
<p>Já o IF deve propor alguma coisa. É preciso escrever o IF e logo depois colocar a condição anaO elif é uma estrutura intermediária dentro da seção if-else no python e deve vir como um complemento a ambos. Quando você já tem um IF e um ELSE, mas precisa de uma condição para especificar outra regra, pode usar o elif.</p>
<a href="https://www.hashtagtreinamentos.com/estruturas-condicionais-no-python?gclid=EAIaIQobChMI8aiIzL3z_QIVGneRCh1Lvgn7EAAYASAAEgKGqPD_BwE" target="_blank">Link em Relação á Estruturas Condicionais.</a>
<p>Exemplo:</p>

<code><pre>
    velocidade = 100

    if velocidade > 110:
        print('Acima da Velocidade Permitida.')
        print('Por Favor Reduzir a sua Velocidade.')
    elif velocidade < 60:
        print('Por Favor Dirigir Acima de 80km/h.')
    else:
        print('Velocidade OK!')
</pre></code>

<h2>Casting</h2>
<p>A função Cast serve para converter o valor de um ripo para outro tipo. Exemplo:</p><br>
<code><pre>
Exemplo 1:    
a = 2 + int('3')
print(a)

Exemplo 2: 
a = 2
b = '3'
print(a + float(b))
</pre></code>

## Slicing

Você pode retornar um intervalo de caracteres usando a sintaxe de slice.
Especifique o índice inicial e o índice final, separados por dois pontos, para retornar uma parte da string.
Exemplo:

</pre></code><p>
b = "Hello, World!" <br>
print(b[2:5]) <br>
#Irá retornar 'llo'. <br>
</p></pre></code>

## Acessando dados pelo index
Sintaxe: nome_da_variável[e o número dentro]<br>

Exemplos com lista:
<code><pre>
          -8      -7       -6       -5        -4       -3       -2        -1
lista = ['Ana', 'Pedro', 'Paula', 'Carlos', 'Diego', 'Diana', 'Sales', 'Hamon']
           1       2         3        4         5        6       7         8

lista = [1:3]   - Imprime do 1 ao 2, pois o último valor não está incluso;
lista = [1:-1]  - Imprime do 1 ao -1 sem inclui-ló;
lista = [1:]    - Imprime do primeiro elemento até o último;
lista = [:-1]   - Imprime do 0 até o -1 sem inclui-ló;
lista = [:]     - Imprime toda a lista;
lista = [::2]   - Imprime a lista, mas saltando de dois em dois;
lista = [::-1]  - Imprime a lista invertida;
del lista = [2] - Deleta o elemento de indice 2.
</pre></code>

<h2>Lista</h2>

Listas são definidas com dois [colchetes] e elas são mutavéis e heterogêneas, assim conseguimos por vários tipos diferentes em uma lista, em Python.  

lista = [] - Lista vazia. <br>
list() - Essa função cria uma lista. <br>
.len(lista) - Essa função retorna a quantidade de elementos contidos em uma lista. <br>
.count() - Retorna a quantidade de vezes que um mesmo elemento está  contido em uma lista. <br>
.append() - Adiciona elementos na lista. <br>
.remove('') - Remove um elemento da lista pelo seu nome. <br>
.pop() - Remove um elemento da lista pela índice. <br>
.index() - Retorna o índice do elemento. <br>


--------------------------------------------------------------------
--------------------------------------------------------------------
#### Outras funções:

\n - quebra linhas.



<!-- Estudar sobre Builtins
Ele é um modulo disponivel para nós. Para acessar digite: __builtins__ -->

<a href="README.md" target="_self"  rel="prev">Voltar á Página Inicial.</a><br>
<a href="#" target="_self"  rel="prev">Página Seguinte.</a>
