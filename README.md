# 🔢 Contador de 1 a 10 em Java

Projeto simples em **Java** criado para praticar a estrutura de repetição `for`.

## 💻 Funcionamento

O programa utiliza um laço `for` para exibir no console os números de **1 até 10**.

### Saída esperada

```text
1
2
3
4
5
6
7
8
9
10
```

## 🧠 Código

```java
public class Main {

    public static void main(String[] args) {

        int i;

        for (i = 1; i <= 10; i = i + 1) {
            System.out.println(i);
        }
    }
}
```

## 📚 O que estou praticando

A estrutura:

```java
for (i = 1; i <= 10; i = i + 1)
```

Funciona assim:

- `i = 1` → o contador começa em 1.
- `i <= 10` → o laço continua enquanto `i` for menor ou igual a 10.
- `i = i + 1` → acrescenta 1 ao contador a cada repetição.

Projeto desenvolvido para estudos de **Java e lógica de programação**. ☕
