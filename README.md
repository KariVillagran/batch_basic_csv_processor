# Spring Batch HelloWorld Project

Este proyecto es un ejemplo básico de Spring Batch que utiliza Java 21. El proyecto contiene una configuración mínima para ejecutar un trabajo batch que imprime "Hello world!" en la consola.

## Requisitos previos

- **Java 21**: Asegúrate de tener instalada la versión 21 de JDK.
- **Maven 3.x** o superior: Para compilar y ejecutar el proyecto.

## Tecnologías utilizadas

- **Java 21**
- **Spring Batch**
- **Spring Framework**
- **Maven**
- **Git**

## Configuración del proyecto

El proyecto incluye la siguiente configuración:

- **Spring Batch con Java-based configuration:** La configuración se realiza mediante anotaciones en una clase Java.
- **HelloWorldJobConfiguration:** Configuración básica de un `Job` y un `Step` que imprimen "Hello world!".

# Como utilizar

Para poder utilizar este repositorio, deberas abrir tu terminal (bash/PowerShell) e ir al directorio del proyecto.

1. Clonar el repositorio

```bash
git clone https://github.com/KariVillagran/batch_hello.git
cd batch-hello
```

2. Compila y ejecuta

```bash
mvn clean install
mvn spring-boot:run
```

Alternativamente, también puedes ejecutar el proyecto directamente usando el comando:

```bash
java -jar target/batch-demo-0.0.1-SNAPSHOT.jar
```