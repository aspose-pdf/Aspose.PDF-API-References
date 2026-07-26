---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Tm-Operator (setzt die Textmatrix) darstellt."
type: docs
weight: 750
url: /de/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Klasse, die den Tm-Operator (setzt die Textmatrix) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Initialisiert den Operator. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Initialisiert den Operator. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Initialisiert den Operator mittels Matrix. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getMatrix](#getMatrix--) | Matrix-Argument des Operators. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrix-Argument des Operators. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Initialisiert den Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a |  | Ein Koeffizient |
| b |  | B-Koeffizient |
| c |  | C-Koeffizient |
| d |  | D-Koeffizient |
| e |  | E-Koeffizient |
| f |  | F-Koeffizient |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Initialisiert den Operator.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Initialisiert den Operator mittels Matrix.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matrix-Argument des Operators.

**Returns:**
Matrix-Objekt

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Matrix-Argument des Operators.

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
