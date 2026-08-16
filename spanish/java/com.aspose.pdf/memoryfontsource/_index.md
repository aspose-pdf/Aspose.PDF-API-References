---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una única fuente de archivo de fuente."
type: docs
weight: 3040
url: /es/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Representa una única fuente de archivo de fuente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Inicializa una nueva instancia de la clase {@code MemoryFontSource}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [dispose](#dispose--) | Libera los recursos internos. Este método está obsoleto, use close() en su lugar. |
| [equals](#equals-java.lang.Object-) | Comprueba si los objetos de origen de archivo de fuente son iguales. |
| [getFontBytes](#getFontBytes--) | Arreglo de bytes del archivo de fuente. |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Inicializa una nueva instancia de la clase {@code MemoryFontSource}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontBytes |  | Arreglo de bytes del archivo de fuente. |

### close {#close--}
```
public void close()
```

Cierra todos los recursos utilizados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera los recursos internos. Este método está obsoleto, use close() en su lugar.

### equals {#equals-java.lang.Object-}
Comprueba si los objetos de origen de archivo de fuente son iguales.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Arreglo de bytes del archivo de fuente.

**Returns:**
matriz byte[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
