---
title: SetTextMatrix
linktitle: SetTextMatrix
second_title: Aspose.PDF for Java API Reference
description: Class representig Tm operator (set text matrix).
type: docs
weight: 750
url: /java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Class representig Tm operator (set text matrix).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Initializes operator. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Initializes operator. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Initializes operator by matrix. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getMatrix](#getMatrix--) | Matrix argument of the operator. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrix argument of the operator. |
| [toString](#toString--) | Returns text representation of operator. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a |  | A coefficient |
| b |  | B coefficient |
| c |  | C coefficient |
| d |  | D coefficient |
| e |  | E coefficient |
| f |  | F coefficient |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Initializes operator.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Initializes operator by matrix.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matrix argument of the operator.

**Returns:**
Matrix object

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Matrix argument of the operator.

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
