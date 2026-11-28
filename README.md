# Exercícios de Java

> 🎓 **Projeto acadêmico** · Análise e Desenvolvimento de Sistemas, PUCPR · 2025

Exercícios de lógica de programação e primeiros passos em orientação a objetos, feitos durante o aprendizado de Java.

## 🧱 Stack

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=flat-square)

## 📚 Exercícios

| Arquivo | O que faz | Conceitos |
|---|---|---|
| [`exercicio.java`](exercicio.java) | Converte temperatura de Celsius para Fahrenheit, repetindo enquanto o usuário quiser | Entrada pelo teclado, laço `do while` |
| [`calcular_fatorial.java`](calcular_fatorial.java) | Calcula o fatorial de um número inteiro | Laço `for`, acumulador |
| [`src/`](src) | Calcula e compara a área de dois triângulos pela fórmula de Heron | Classes, objetos, pacotes |

## ▶️ Como rodar

Exercícios avulsos:
```bash
javac exercicio.java && java exercicio
javac calcular_fatorial.java && java calcular_fatorial
```

Exercício dos triângulos:
```bash
javac -d out src/entities/triangulo.java src/application/program.java
java -cp out application.program
```

## ⚠️ Observação

O fatorial usa `int`, então o resultado fica incorreto a partir de 13! (o valor passa do limite do tipo). Trocar para `long` resolve até 20!, e `BigInteger` resolve para qualquer número.
