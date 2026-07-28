---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar Tm-operatorn (sätter textmatris)."
type: docs
weight: 750
url: /sv/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Klass som representerar Tm-operatorn (sätter textmatris).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Initierar operatorn. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Initierar operatorn. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Initierar operator med matris. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getMatrix](#getMatrix--) | Matrisargument för operatorn. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrisargument för operatorn. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Initierar operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a |  | A-koefficient |
| b |  | B-koefficient |
| c |  | C-koefficient |
| d |  | D-koefficient |
| e |  | E-koefficient |
| f |  | F-koefficient |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Initierar operatorn.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Initierar operator med matris.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matrisargument för operatorn.

**Returns:**
Matrix-objekt

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Matrisargument för operatorn.

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.
