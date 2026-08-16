---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el nivel de gris para operaciones con trazo."
type: docs
weight: 650
url: /es/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Clase que representa el nivel de gris para operaciones con trazo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Inicializa el operador con el color especificado. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getColor](#getColor--) | Devuelve el color especificado por el operador. |
| [getGray](#getGray--) | Obtiene o establece el nivel del valor de gris. |
| [setGray](#setGray-double-) | Obtiene o establece el nivel del valor de gris. |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Inicializa el operador con el color especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gris |  | El nivel del valor de gris. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getColor {#getColor--}
```
public Color getColor()
```

Devuelve el color especificado por el operador.

**Returns:**
Color especificado por el operador.

### getGray {#getGray--}
```
public final double getGray()
```

Obtiene o establece el nivel del valor de gris.

**Returns:**
valor double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Obtiene o establece el nivel del valor de gris.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
