# HerancaJava

Ambiente de programação Java com JDK, compilador e execução do arquivo `main.java`.

## Run & Operate

- Use o workflow **Executar main.java** para rodar o arquivo.
- `java main.java` — executar o arquivo diretamente.
- `javac main.java && java main` — compilar e executar separadamente.
- `java -version` e `javac -version` — conferir runtime e compilador.

## Stack

- Java 19.0.2 com GraalVM CE 22.3.1
- JDK, incluindo `java`, `javac` e Maven

## Where things live

- `main.java` — ponto de entrada inicial; será mantido vazio após a validação solicitada.

## Architecture decisions

- O workflow executa `main.java` quando há código e informa quando o arquivo está vazio.

## Product

Projeto-base HerancaJava para desenvolver e executar código Java.

## User preferences

- Após validar o ambiente, deixar `main.java` completamente em branco.

## Gotchas

- Para executar o arquivo vazio, adicione primeiro uma classe com método `main`.

## Pointers

- O launcher Java aceita execução direta no formato `java main.java`.
