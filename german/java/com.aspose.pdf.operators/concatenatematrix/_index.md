---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den cm‑Operator (Matrix an die aktuelle Transformationsmatrix anhängen) darstellt."
type: docs
weight: 140
url: /de/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Klasse, die den cm‑Operator (Matrix an die aktuelle Transformationsmatrix anhängen) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Konstruktor für die Operator-Klasse. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Konstruktor für die Operator-Klasse. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Initialisiert den Operator mittels Matrix. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getMatrix](#getMatrix--) | Matrix-Argument des Operators. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrix-Argument des Operators. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Konstruktor für die Operator-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a |  | Ein Koeffizient |
| b |  | B-Koeffizient |
| c |  | C-Koeffizient |
| d |  | D-Koeffizient |
| e |  | E-Koeffizient |
| f |  | F-Koeffizient |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Konstruktor für die Operator-Klasse.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung der Darstellung
