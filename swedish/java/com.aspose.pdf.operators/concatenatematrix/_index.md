---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar cm-operatorn (concatenate matrix to current transformation matrix)."
type: docs
weight: 140
url: /sv/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Klassen representerar cm-operatorn (concatenate matrix to current transformation matrix).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Konstruktor för operator-klassen. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Konstruktor för operator-klassen. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Initierar operator med matris. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getMatrix](#getMatrix--) | Matrisargument för operatorn. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrisargument för operatorn. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Konstruktor för operator-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a |  | A-koefficient |
| b |  | B-koefficient |
| c |  | C-koefficient |
| d |  | D-koefficient |
| e |  | E-koefficient |
| f |  | F-koefficient |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Konstruktor för operator-klassen.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av representation
