# Desafio Classes

## O que são classes Wrappers?
<p>Classes wrappers são 
Wrappers vem do verbo inglês “wrap” que significa envolver. Tem como principal função “envolver coisas” adicionando funcionalidades à ela.</p>

<p>Uma definição simplista de uma classe wrapper é:
Uma classe que possui um atributo de um tipo primitivo correspondente, o que permite realizar operações básicas com esse valor.</p>

<p>Um ponto importante a ser observado é que o atributo interno do tipo primitivo é final, ou seja imutável. Uma vez atribuído um valor a esse atributo, não será possível modificá-lo. Assim podemos convencionar que todas as classes wrappers são imutáveis. Dessa forma, podemos evitar alguns erros ao tentar atribuir um valor novo.
</p>

### Classe Java.lang.Integer
A classe inteira é uma classe wrapper para o tipo primitivo int que contém vários métodos para lidar efetivamente com um valor int, como convertê-lo em uma representação de string e vice-versa. Um objeto da classe Integer pode conter um único valor int. 

Construtores: 

Integer (int b): Cria um objeto Integer inicializado com o valor fornecido.



