---
title: ConcatenateMatrix
second_title: Aspose.PDF for Java API Reference
description: Class representing cm operator concatenate matrix to current transformation matrix.
type: docs
weight: 23
url: /java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ConcatenateMatrix extends Operator
```

Class representing cm operator (concatenate matrix to current transformation matrix).
## Constructors

| Constructor | Description |
| --- | --- |
| [ConcatenateMatrix(int index, ICommand command)](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ConcatenateMatrix(double a, double b, double c, double d, double e, double f)](#ConcatenateMatrix-double-double-double-double-double-double-) | Constructor for operator class. |
| [ConcatenateMatrix(Matrix m)](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Initializes operator by matrix. |
## Methods

| Method | Description |
| --- | --- |
| [getMatrix()](#getMatrix--) | Matrix argument of the operator. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Matrix argument of the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [toCommand()](#toCommand--) |  |
### ConcatenateMatrix(int index, ICommand command) {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ConcatenateMatrix(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ConcatenateMatrix(double a, double b, double c, double d, double e, double f) {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A coefficient |
| b | double | B coefficient |
| c | double | C coefficient |
| d | double | D coefficient |
| e | double | E coefficient |
| f | double | F coefficient |

### ConcatenateMatrix(Matrix m) {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
```
public ConcatenateMatrix(Matrix m)
```


Initializes operator by matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| m | [Matrix](../../com.aspose.pdf/matrix) | Transfomation matrix. |

### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Matrix argument of the operator.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix object
### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Matrix argument of the operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Matrix object |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of representation
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
