---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica las dimensiones de los márgenes de una página impresa."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Especifica las dimensiones de los márgenes de una página impresa.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Inicializa una nueva instancia de la clase Margins con márgenes de 1 pulgada de ancho. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Inicializa una nueva instancia de la clase Margins con los márgenes izquierdo, derecho, superior e inferior especificados. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Obtiene una copia duplicada de este objeto, miembro por miembro. |
| [equals](#equals-java.lang.Object-) | Compara este Margins con el Object especificado para determinar si tienen las mismas dimensiones. (Sobrescribe Object.Equals(Object).) |
| [getBottom](#getBottom--) | Obtiene o establece el margen inferior, en centésimas de pulgada. |
| [getLeft](#getLeft--) | Obtiene o establece el ancho del margen izquierdo, en centésimas de pulgada. |
| [getRight](#getRight--) | Obtiene o establece el ancho del margen derecho, en centésimas de pulgada. |
| [getTop](#getTop--) | Obtiene o establece el ancho del margen superior, en centésimas de pulgada. |
| [hashCode](#hashCode--) | Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compara dos Margins para determinar si tienen las mismas dimensiones. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compara dos Margins para determinar si tienen anchuras desiguales. |
| [setBottom](#setBottom-int-) | Obtiene o establece el margen inferior, en centésimas de pulgada. |
| [setLeft](#setLeft-int-) | Obtiene o establece el ancho del margen izquierdo, en centésimas de pulgada. |
| [setRight](#setRight-int-) | Obtiene o establece el ancho del margen derecho, en centésimas de pulgada. |
| [setTop](#setTop-int-) | Obtiene o establece el ancho del margen superior, en centésimas de pulgada. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Inicializa una nueva instancia de la clase Margins con márgenes de 1 pulgada de ancho.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Inicializa una nueva instancia de la clase Margins con los márgenes izquierdo, derecho, superior e inferior especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda |  | valor int |
| derecha |  | valor int |
| arriba |  | valor int |
| inferior |  | valor int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Obtiene una copia duplicada de este objeto, miembro por miembro.

**Returns:**
Objeto PrinterMargins

### equals {#equals-java.lang.Object-}
Compara este Margins con el Object especificado para determinar si tienen las mismas dimensiones. (Sobrescribe Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Obtiene o establece el margen inferior, en centésimas de pulgada.

**Returns:**
valor int

### getLeft {#getLeft--}
```
public int getLeft()
```

Obtiene o establece el ancho del margen izquierdo, en centésimas de pulgada.

**Returns:**
valor int

### getRight {#getRight--}
```
public int getRight()
```

Obtiene o establece el ancho del margen derecho, en centésimas de pulgada.

**Returns:**
valor int

### getTop {#getTop--}
```
public int getTop()
```

Obtiene o establece el ancho del margen superior, en centésimas de pulgada.

**Returns:**
valor int

### hashCode {#hashCode--}
```
public int hashCode()
```

Devuelve un valor de código hash para el objeto. Este método es compatible para el beneficio de tablas hash como las proporcionadas por {@link java.util.HashMap}. <p> El contrato general de {@code hashCode} es: <ul> <li>Siempre que se invoque en el mismo objeto más de una vez durante la ejecución de una aplicación Java, el método {@code hashCode} debe devolver consistentemente el mismo entero, siempre que no se modifique la información utilizada en las comparaciones {@code equals} del objeto. Este entero no necesita permanecer consistente de una ejecución de una aplicación a otra ejecución de la misma aplicación. <li>Si dos objetos son iguales según el método {@code equals(Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos debe producir el mismo resultado entero. <li>No es <em>necesario</em> que si dos objetos son desiguales según el método {@link java.lang.Object#equals(java.lang.Object)}, entonces llamar al método {@code hashCode} en cada uno de los dos objetos produzca resultados enteros distintos. Sin embargo, el programador debe ser consciente de que producir resultados enteros distintos para objetos desiguales puede mejorar el rendimiento de las tablas hash. </ul> <p> En la medida de lo razonablemente práctico, el método hashCode definido por la clase {@code Object} devuelve enteros distintos para objetos distintos. (Esto suele implementarse convirtiendo la dirección interna del objeto en un entero, pero esta técnica de implementación no es requerida por el lenguaje de programación Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compara dos Margins para determinar si tienen las mismas dimensiones.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compara dos Margins para determinar si tienen anchuras desiguales.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Obtiene o establece el margen inferior, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Obtiene o establece el ancho del margen izquierdo, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Obtiene o establece el ancho del margen derecho, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Obtiene o establece el ancho del margen superior, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
