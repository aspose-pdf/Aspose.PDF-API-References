---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador TL (establece la interlínea del texto)."
type: docs
weight: 740
url: /es/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Clase que representa el operador TL (establece la interlínea del texto).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Constructor para el operador de interlineado de texto. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getLeading](#getLeading--) | Obtiene el interlineado del texto. |
| [setLeading](#setLeading-double-) | Establece el interlineado del texto. |
| [toString](#toString--) | Produce el código de texto del operador. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Constructor para el operador de interlineado de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leading |  | Interlineado del texto. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getLeading {#getLeading--}
```
public double getLeading()
```

Obtiene el interlineado del texto.

**Returns:**
valor double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Establece el interlineado del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Produce el código de texto del operador.

**Returns:**
Representación textual del operador.
