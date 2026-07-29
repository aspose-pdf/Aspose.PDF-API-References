---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa todas las fuentes instaladas en el sistema."
type: docs
weight: 4770
url: /es/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Representa todas las fuentes instaladas en el sistema.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Inicializa una nueva instancia de la clase. |

## Métodos

| Método | Descripción |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Comprueba si los objetos de origen de fuentes del sistema son iguales. |
| [getFontDefinitions](#getFontDefinitions--) | Solo para uso interno |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Inicializa una nueva instancia de la clase.

### equals {#equals-java.lang.Object-}
Comprueba si los objetos de origen de fuentes del sistema son iguales.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Solo para uso interno

**Returns:**
Objeto FontDefinition[]

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
