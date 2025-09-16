# Descripción de la Arquitectura de Software

Este repositorio contiene la documentación del Sistema de Reserva Hotelera

## Objetivo
Aprender a trabajar con documentación técnica usando un flujo *docs-as-code*
- Texto plano con **AsciiDoc y Asciidoctor**
- Control de versiones con GitHub
- Publicación automática de HTML y PDF con **CI/CD***
- Inclusion de diagramas creados en **Enterprise Architect**

## Estructura del Proyecto
docs/         -> Documentación en AsciiDoc
images/       -> Diagramas exportados desde Enterprise Architect
build/        -> Salida generada (ignorada en git)

## Requisitos
- Ruby (con Asciidoctor y Asciidoctor PDF instalados)
- VS Code con la extensión Asciidoc by Asciidoctor

## Compilacion local (bash)
asciidoctor -D build docs/index.adoc
asciidoctor-pdf -o build/index.pdf docs/index.adoc

Prueba de generacion de documento 2
