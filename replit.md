# HerancaJava

Ambiente de programação Java com JDK, compilador e execução do arquivo `main.java`.

## Run & Operate

- Use o workflow **Executar main.java** para rodar o arquivo.
- `javac -sourcepath . -d build/classes main.java && java -cp build/classes main` — compilar e executar a partir da raiz.
- `java -version` e `javac -version` — conferir runtime e compilador.

## Stack

- Java 19.0.2 com GraalVM CE 22.3.1
- JDK, incluindo `java`, `javac` e Maven

## Where things live

- `main.java` — ponto de entrada do programa.
- `modelos/Pessoa.java` — classe `Pessoa`, no pacote `modelos`.

## Architecture decisions

- O workflow compila o ponto de entrada e resolve classes em pacotes usando a raiz como source path.

## Product

Projeto-base HerancaJava para desenvolver e executar código Java.

## Gotchas

- Compile a partir da raiz do projeto para que o compilador encontre arquivos dentro de diretórios de pacotes.

