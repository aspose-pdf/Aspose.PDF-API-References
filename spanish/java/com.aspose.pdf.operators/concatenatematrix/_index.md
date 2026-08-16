---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador cm (concatena la matriz a la matriz de transformación actual)."
type: docs
weight: 140
url: /es/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Clase que representa el operador cm (concatena la matriz a la matriz de transformación actual).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Constructor de la clase operador. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Constructor de la clase operador. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Inicializa el operador mediante una matriz. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getMatrix](#getMatrix--) | Argumento de matriz del operador. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumento de matriz del operador. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Constructor de la clase operador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a |  | Coeficiente A |
| b |  | Coeficiente B |
| c |  | Coeficiente C |
| d |  | Coeficiente D |
| e |  | Coeficiente E |
| f |  | Coeficiente F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Constructor de la clase operador.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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

Devuelve la representación de texto del operador.

**Returns:**
Representación textual de la representación
