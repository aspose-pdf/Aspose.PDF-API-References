---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador Tm (define a matriz de texto)."
type: docs
weight: 750
url: /pt/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Classe que representa o operador Tm (define a matriz de texto).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Inicializa o operador. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Inicializa o operador. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Inicializa o operador por matriz. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getMatrix](#getMatrix--) | Argumento de matriz do operador. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumento de matriz do operador. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Inicializa o operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a |  | Coeficiente A |
| b |  | Coeficiente B |
| c |  | Coeficiente C |
| d |  | Coeficiente D |
| e |  | Coeficiente E |
| f |  | Coeficiente F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Inicializa o operador.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Inicializa o operador por matriz.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argumento de matriz do operador.

**Returns:**
Objeto Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argumento de matriz do operador.

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.
