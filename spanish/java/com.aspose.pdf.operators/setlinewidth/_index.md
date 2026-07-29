---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador w (establece el ancho de línea)."
type: docs
weight: 690
url: /es/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Clase que representa el operador w (establece el ancho de línea).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Inicializa el operador con el valor de ancho. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getWidth](#getWidth--) | Obtiene el ancho de la línea. |
| [setWidth](#setWidth-double-) | Establece el ancho de la línea. |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Inicializa el operador con el valor de ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Valor del ancho. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho de la línea.

**Returns:**
ancho de la línea.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho de la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | ancho de la línea. |

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
