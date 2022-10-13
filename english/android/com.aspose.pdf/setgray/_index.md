---
title: Operator.SetGray
second_title: Aspose.PDF for Java API Reference
description: Set gray level for non-stroking operations.
type: docs
weight: 67
url: /java/com.aspose.pdf/operator.setgray/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetGray extends Operator.SetColorOperator
```

Set gray level for non-stroking operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [SetGray(double gray)](#SetGray-double-) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns string represnetation of operator. |
### SetGray(double gray) {#SetGray-double-}
```
public SetGray(double gray)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gray | double | The level of gray value. |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by operator.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Color specified by operator.
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


Returns string represnetation of operator.

**Returns:**
java.lang.String - String representation of operator.
