## Proyecto - Listas

Plantilla básica para proyecto de Java

# Diagrama de clases
[Editor en línea](https://mermaid.live/)
```mermaid
---
title: Listas
---
classDiagram
      direction LR
      class ClaseParaDepurar
      ClaseParaDepurar: -double suma
      ClaseParaDepurar: -List~Double~ lista
      ClaseParaDepurar: +echaCuentas()

      class Principal
      Principal: +main()

      Principal-->ClaseParaDepurar
```
[Referencia-Mermaid](https://mermaid.js.org/syntax/classDiagram.html)

* Ejecutar

```
gradle run
```
* Probar

```
gradle test
```
* Generar el Diagrama de Secuencia 

```
gradle appmap test
```
El Diagrama de Secuencia se puede consultar en `/app/build/appmap/junit/**.json`

[Referencia Appmap.io](https://appmap.io/)

Los comandos anteriores están considerados para un ambiente Linux

