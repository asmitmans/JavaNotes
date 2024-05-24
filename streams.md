# Streams en Java

<!-- Tags: Java, Streams, Operaciones Intermedias, filter, map -->

## Introducción

Los Streams permiten procesar secuencias de datos de manera declarativa.

```java
List<String> nombres = Arrays.asList("Ana", "Carlos", "Beatriz");
nombres.stream()
       .filter(nombre -> nombre.startsWith("A"))
       .forEach(System.out::println);