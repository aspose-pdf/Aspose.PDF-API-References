---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador Tf (establecer la fuente y el tamaño del texto)."
type: docs
weight: 470
url: /es/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Clase que representa el operador Tf (establecer la fuente y el tamaño del texto).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Constructor de la clase operador. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Constructor para el programa de escritura. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getName](#getName--) | Obtiene el nombre de la fuente. |
| [getSize](#getSize--) | Obtiene el tamaño del texto. |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Constructor de la clase operador.

### SelectFont {#SelectFont-java.lang.String-double-}
Constructor para el programa de escritura.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre de la fuente.

**Returns:**
valor String

### getSize {#getSize--}
```
public double getSize()
```

Obtiene el tamaño del texto.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
