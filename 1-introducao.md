# 1. Introdução à lógica de programação com Python

![](.pastes/2019-09-01-09-11-58.png)

**Python é uma linguagem de programação com código aberto, de alto nível, tipicamente usada para aplicações web ou linguagens de scripts para administração de sistemas.**

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
print ('Olá, nome)
```