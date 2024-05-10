# Ejecución de Escenarios Gherkin con Maven

Este proyecto utiliza Maven para ejecutar escenarios Gherkin que están etiquetados con `@registro` y `@iniciarSesion`.

## Requisitos

- Java 11
- Maven
- IntelliJ IDEA
- Cucumber

## Configuración del Proyecto

Asegúrate de tener instalado Java 11 y Maven en tu sistema. Este proyecto está desarrollado utilizando IntelliJ IDEA, un entorno de desarrollo integrado (IDE) popular para Java.

1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en IntelliJ IDEA.
3. Configura tu entorno de desarrollo para utilizar Java 11 y Maven.

## Ejecución de Escenarios Gherkin

Para ejecutar los escenarios Gherkin etiquetados con `@registro` y `@iniciarSesion`, sigue estos pasos:

1. Abre una terminal en la raíz del proyecto.
2. Ejecuta el siguiente comando Maven:

```bash
mvn test -Dcucumber.filter.tags="@registro or @iniciarSesion"
