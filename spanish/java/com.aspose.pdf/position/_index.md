---
title: "Position"
linktitle: "Position"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un objeto de posición"
type: docs
weight: 3940
url: /es/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Representa un objeto de posición

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Position](#Position-double-double-) | Inicializa una nueva instancia de la clase {@code Position} |

## Métodos

| Método | Descripción |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina si el objeto especificado es igual al objeto {@code Position} actual. |
| [getXIndent](#getXIndent--) | Obtiene la coordenada X del objeto |
| [getYIndent](#getYIndent--) | Obtiene la coordenada Y del objeto |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | Establece la coordenada X del objeto |
| [setYIndent](#setYIndent-double-) | Establece la coordenada Y del objeto |
| [toString](#toString--) | Obtiene la representación en cadena del objeto {@code Position} actual. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Inicializa una nueva instancia de la clase {@code Position}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xIndent |  | Valor de la coordenada X. |
| yIndent |  | Valor de la coordenada Y. |

### equals {#equals-java.lang.Object-}
Determina si el objeto especificado es igual al objeto {@code Position} actual.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtiene la coordenada X del objeto

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtiene la coordenada Y del objeto

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Establece la coordenada X del objeto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Establece la coordenada Y del objeto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Obtiene la representación en cadena del objeto {@code Position} actual.

**Returns:**
Representación en cadena del objeto Position.
