# Respostas de questões dissertativas
## Q1 - Os comandos corretos são:
- javac Avaliacao.java < Compila o programa;
- java Avaliacao < Executa o programa;
---
## Q2:
- Ocorre erro de compilação, onde é informado que a variável *contador* não foi inicializada, e por ser atribuida como *int* é necessário inicializar com qualquer valor do tipo inteiro.
- Um exemplo correto seria: *int contador=0;*
---
## Q3:
- O operador *&& (and / E)* avalia se os dois lados da condição são verdadeiros;
- Como o primeiro lado é *falso*, a segunda condição não é avaliada, dessa forma o incremento em *b* não ocorre e é impresso o resultado de *a-b*;
- Caso *a* fosse *verdadeiro* ocorreria o incremento em *b* que passaria a valer *1*;
---
## Q4
- O comando *switch...case* testa todos os casos e imprime o valor em cada caso;
- Normalmente é usado com um *break* no final de cada caso;
- Sem o *break* todos os casos são testados;
---
## Q5
```Java
// Código da questão
public class Exemplo {
    public static void main(String[] args) {
        int a = 10;
        int b = 1;
        System.out.println("Soma: " + a + b);
    }
}

// Código corrigido
public class Exemplo {
    public static void main(String[] args) {
        int a = 10;
        int b = 1;
        int soma = a +b;
        System.out.println("Soma: " + soma);
    }
}

```