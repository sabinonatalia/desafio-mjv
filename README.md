# Desafio Classes

## O que são classes Wrappers?
<p>Classes wrappers são 
Wrappers vem do verbo inglês “wrap” que significa envolver. Tem como principal função “envolver coisas” adicionando funcionalidades à ela.</p>

<p>Uma definição simplista de uma classe wrapper é:
Uma classe que possui um atributo de um tipo primitivo correspondente, o que permite realizar operações básicas com esse valor.</p>

<p>Um ponto importante a ser observado é que o atributo interno do tipo primitivo é final, ou seja imutável. Uma vez atribuído um valor a esse atributo, não será possível modificá-lo. Assim podemos convencionar que todas as classes wrappers são imutáveis. Dessa forma, podemos evitar alguns erros ao tentar atribuir um valor novo.
</p>

### Classe Java.lang.Integer
A classe inteira é uma classe **wrappers** para o tipo primitivo int que contém vários métodos para lidar efetivamente com um valor int, como convertê-lo em uma representação de string e vice-versa. Um objeto da classe Integer pode conter um único valor int.



- `Integer (int b)`: Cria um objeto Integer inicializado com o valor fornecido.
<p>Sintaxe:</p>

```
public Integer(int b)
```
Parâmetros:

```
b : value with which to initialize
```

- `Integer (String s)`: Cria um objeto Integer inicializado com o valor int fornecido pela representação de string. A raiz padrão é considerada 10.

Sintaxe: 
```
public Integer(String s) throws NumberFormatException
```
Parâmetros:
```
s : string representation of the int value 
```

### Classe Java.Lang.Double 

A classe dupla é uma classe wrapper para o tipo primitivo double que contém vários métodos para lidar efetivamente com um valor duplo, como convertê-lo em uma representação de string e vice-versa. Um objeto da classe Double pode conter um único valor duplo. Existem principalmente dois construtores para inicializar um objeto Double:

- `Double (double b)`: Cria um objeto Double inicializado com o valor fornecido. 

Sintaxe:
```
public Double(Double d)
````
Parâmetros: 

```
d : value with which to initialize
```
- `Double (String s)`: Cria um objeto Double inicializado com o valor double analisado fornecido pela representação de string. A raiz padrão é considerada 10. 

Sintaxe:

```
public Double(String s) throws NumberFormatException
```
Parâmetros:

```
s : string representation of the byte value 
```

### Referências
