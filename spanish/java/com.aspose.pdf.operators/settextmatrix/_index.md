---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador Tm (establece la matriz de texto)."
type: docs
weight: 750
url: /es/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Clase que representa el operador Tm (establece la matriz de texto).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Inicializa el operador. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Inicializa el operador. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Inicializa el operador mediante una matriz. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getMatrix](#getMatrix--) | Argumento de matriz del operador. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumento de matriz del operador. |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Inicializa el operador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a |  | Coeficiente A |
| b |  | Coeficiente B |
| c |  | Coeficiente C |
| d |  | Coeficiente D |
| e |  | Coeficiente E |
| f |  | Coeficiente F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Inicializa el operador.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Inicializa el operador mediante una matriz.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argumento de matriz del operador.

**Returns:**
Objeto Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argumento de matriz del operador.

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
