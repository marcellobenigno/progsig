# 1. Introdução à lógica de programação com Python

![](.pastes/2019-09-01-09-11-58.png)

**Python é uma linguagem de programação com código aberto, de alto nível, tipicamente usada para aplicações web ou linguagens de scripts para administração de sistemas.**

A linguagem foi criada em 1989 por **Guido Van Rossum** e o seu nome foi uma homenagem ao grupo humorístico britânico **Monty Python** (*Monty Python's Flying Circus*), embora muitas pessoas façam associação com o réptil do mesmo nome 🐍 .

![guido](.pastes/2019-09-01-19-31-54.png)

### Por que Python?

*extraído do link: https://pythonhelp.wordpress.com/por-que-python/*

#### Java:
``` java
public class Hello
{
    public static void main(String args[]) {
        java.util.Scanner s = new java.util.Scanner(System.in);
        System.out.print("Digite seu nome:");
        String nome = s.nextLine();
        System.out.println("Olá, " + nome);
    }
}
```
#### C:
``` c
#include <stdio.h>;
int main()
{
    char nome[200];
    printf("Digite seu nome:");
    scanf("%s", nome);
    printf("Olá, %s\n", nome);
    return 0;
}
```

#### Python: 😍
``` python
nome = input('Digite seu nome:')
print('Olá, nome)
```


### Instruções de atribuição:

Uma instrução de atribuição cria uma nova variável e dá um valor a ela:

``` python
nome = 'Marcello'
idade = 42
peso = 98.50
```

#### Nomes de variáveis:

Podem conter tanto letras como números, mas não podem começar com um número. É convenção utilizar letras minúsculas para nomes de variáveis, porém para indicar constantes, a convenção é colocar o nome da variável em *uppercase* (ex. `VARIAVEL=12`).

O caractere *underline* (_) pode aparecer no nome de uma de variável. Muitas vezes é usado em nomes compostos, como `data_nascimento` ou `area_m2`.

**Exemplos de nomes ilegais para variáveis:**

``` python
>>> 10v = 1000
SyntaxError: invalid syntax
>>> email@ = 'joao@email.com'
SyntaxError: invalid syntax
>>> class = 'Programação'
SyntaxError: invalid syntax
```

`10v` é ilegal porque começa com um número, `email@` possui um caractere ilegal. Já `class` é uma palavra reservada não pode ser utilizada como nome de variável.

São palavras reservadas em Python:

```
and         del         from        None        True
as          elif        global      nonlocal    try
assert      else        if          not         while
break       except      import      or          with
class       False       in          pass        yield
continue    finally     is          raise
def         for         lambda      return
```

### Tipos de Variáveis:

- **Numéricos**: armazenam números. São: inteiros (int), de ponto flutuante (float) e complexos (complex);
- **Literais**: armazenam caracteres (qualquer um do teclado) ou sequências de caracteres (string);
- **Lógicos**: booleanos, armazenam verdadeiro ou falso (bool).

``` python
>>> valor = 100
>>> type(valor)
<class 'int'>
>>> perimetro_m = 237.95
>>> type(perimetro_m)
<class 'float'>
>>> nome = 'Maria'
>>> type(nome)
<class 'str'>
>>> cond = True
>>> type(cond)
<class 'bool'>
```
📚  Sugestão de leitura:  https://realpython.com/python-data-types/