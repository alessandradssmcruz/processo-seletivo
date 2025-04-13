
# Desafio Controle de Fluxo - DIO

Este projeto foi desenvolvido como parte do **desafio prático de Controle de Fluxo** do curso da Digital Innovation One (DIO). O objetivo é aplicar estruturas de controle com exceções personalizadas em um programa simples em Java.

## 📋 Descrição do Desafio

O sistema recebe dois números inteiros via terminal e realiza uma contagem com base na diferença entre eles. Caso o primeiro número seja maior que o segundo, o sistema lança uma exceção customizada com a mensagem:

```
O segundo parâmetro deve ser maior que o primeiro
```

Se os parâmetros forem válidos, o programa imprime no console mensagens numeradas como:

```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
```

## 🚀 Como executar

1. Certifique-se de que você tem o Java instalado (versão 17 ou superior recomendada).
2. Clone ou baixe este repositório.
3. Compile os arquivos:

```bash
javac Contador.java ParametrosInvalidosException.java
```

4. Execute o programa:

```bash
java Contador
```

5. Insira os dois números solicitados no terminal.

## 📁 Estrutura do Projeto

```
DesafioControleFluxo/
│
├── Contador.java                    # Classe principal com a lógica do programa
├── ParametrosInvalidosException.java  # Exceção personalizada
└── README.md                        # Este arquivo
```

## 🛠️ Tecnologias utilizadas

- Java
- VS Code ou IDE de sua preferência

## 📚 Conceitos aplicados

- Estruturas de repetição (`for`)
- Tratamento de exceções
- Criação de exceção customizada
- Entrada de dados via `Scanner`

## ✍️ Autor

Projeto desenvolvido por Suzy Cruz durante o curso de Java Básico na [Digital Innovation One](https://www.dio.me/).
