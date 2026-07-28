---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una única fuente de archivo de fuente."
type: docs
weight: 1450
url: /es/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Representa una única fuente de archivo de fuente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Inicializa una nueva instancia de la clase {@code FileFontSource}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Comprueba si los objetos de origen de archivo de fuente son iguales. |
| [getFilePath](#getFilePath--) | Ruta al archivo de fuente. |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java <span style="font-size:70%"><sup>TM</sup></span>.) |
| [setFilePath](#setFilePath-java.lang.String-) | Ruta al archivo de fuente. |

### FileFontSource {#FileFontSource-java.lang.String-}
Inicializa una nueva instancia de la clase {@code FileFontSource}.

### equals {#equals-java.lang.Object-}
Comprueba si los objetos de origen de archivo de fuente son iguales.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Ruta al archivo de fuente.

**Returns:**
valor String

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique ninguna información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java <span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Ruta al archivo de fuente.
