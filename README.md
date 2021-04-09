# Práctica 1 - Curso de Patrones de Diseño
# Undo / Redo

Realizar el juego del Mastermind con la funcionalidad de Undo / Redo.

Esta práctica se debe realizar siguiendo la analogía del juego de TicTacToe, en la versión Undo / Redo que hemos visto en la clase 9 del [curso de Patrones de Diseño](https://escuela.it/cursos/patrones) de EscuelaIT.

Para la realización de la práctica vamos a partir de una base de código que se encuentra en este mismo repositorio. Este es el código del Mastermind con la técnica del doble despacho, sobre el que agregaremos los patrones y funcionalidad necesaria para construir el Undo / Redo con un diseño correcto.

Recuerda que los requisitos y otras informaciones relativas al juego de Mastermind los hemos visto en los cursos anteriores (Curso de diseño y anteriores). Los [requisitos de esta versión se pueden ver en este enlace](https://github.com/USantaTecla-project-mastermind/requirements/tree/master/3.UndoRedo).

A continuación encuentras el README que había en el repositorio original, de USantaTecla, que se ha copiado en este repositorio para la práctica.

<h1 align="center">Welcome to Master Mind. Solución 4.2. ** dv.+doubleDispathing **
 👋</h1>
<p>
  <a href="/docs" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> Master Mind. Solución dv.withdoubleDispathing

## Install

```sh
mvn install
```

## Usage

For Console edition:

Edit pom.xml line 42 for this:

```sh
<mainClass>usantatecla.mastermind.ConsoleMastermind</mainClass>
```
And then:

```sh
mvn clean
mvn package
java -jar target/mastermind-1.0-SNAPSHOT.jar
```

For Graphics edition:

Edit pom.xml line 42 for this:

```sh
<mainClass>usantatecla.mastermind.GraphicsMastermind</mainClass>
```
And then:

```sh
mvn clean
mvn package
java -jar target/mastermind-1.0-SNAPSHOT.jar
```

## Run tests

```sh
mvn test
```

## Author

👤 **USantaTecla**

* Github: [@USantaTecla](https://github.com/USantaTecla)


Note that you should have to [install JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Maven](https://maven.apache.org/install.html) as prerequisite.