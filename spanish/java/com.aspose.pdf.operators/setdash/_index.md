---
title: "SetDash"
linktitle: "SetDash"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador d (establece el patrón de guiones de línea)."
type: docs
weight: 610
url: /es/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Clase que representa el operador d (establece el patrón de guiones de línea).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Crea el operador de patrón de guiones. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getPattern](#getPattern--) | Patrón de guiones. Los elementos de la matriz deben ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guión y espacio son iguales. |
| [getPhase](#getPhase--) | Fase de guiones. Antes de comenzar a trazar una ruta, se debe ciclar la matriz de guiones, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta, y la matriz de guiones se usará cíclicamente a partir de ese punto. |
| [setPattern](#setPattern-int:A-) | Patrón de guiones. Los elementos de la matriz deben ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guión y espacio son iguales. |
| [setPhase](#setPhase-int-) | Fase de guiones. Antes de comenzar a trazar una ruta, se debe ciclar la matriz de guiones, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta, y la matriz de guiones se usará cíclicamente a partir de ese punto. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Obtiene la representación en cadena del operador. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Crea el operador de patrón de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| patrón |  | Matriz que define el patrón de guiones. |
| fase |  | Fase de guiones. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Patrón de guiones. Los elementos de la matriz deben ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guión y espacio son iguales.

**Returns:**
matriz de int

### getPhase {#getPhase--}
```
public int getPhase()
```

Fase de guiones. Antes de comenzar a trazar una ruta, se debe ciclar la matriz de guiones, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta, y la matriz de guiones se usará cíclicamente a partir de ese punto.

**Returns:**
valor int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Patrón de guiones. Los elementos de la matriz deben ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guión y espacio son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Fase de guiones. Antes de comenzar a trazar una ruta, se debe ciclar la matriz de guiones, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta, y la matriz de guiones se usará cíclicamente a partir de ese punto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

¡Solo para uso interno!

**Returns:**
Valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Obtiene la representación en cadena del operador.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
