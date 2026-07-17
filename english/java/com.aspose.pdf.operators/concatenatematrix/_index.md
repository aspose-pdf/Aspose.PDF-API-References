---
title: ConcatenateMatrix
linktitle: ConcatenateMatrix
second_title: Aspose.PDF for Java API Reference
description: Class representing cm operator (concatenate matrix to current transformation matrix).
type: docs
weight: 140
url: /java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Class representing cm operator (concatenate matrix to current transformation matrix).

## Constructors

| Constructor | Description |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Constructor for operator class. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Constructor for operator class. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Initializes operator by matrix. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getMatrix](#getMatrix--) | Matrix argument of the operator. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Matrix argument of the operator. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a |  | A coefficient |
| b |  | B coefficient |
| c |  | C coefficient |
| d |  | D coefficient |
| e |  | E coefficient |
| f |  | F coefficient |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Constructor for operator class.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of representation
