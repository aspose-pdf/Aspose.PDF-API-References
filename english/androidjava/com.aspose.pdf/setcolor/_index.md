---
title: Operator.SetColor
second_title: Aspose.PDF for Java API Reference
description: Represents class for sc operator set color for non-stroknig operations.
type: docs
weight: 58
url: /java/com.aspose.pdf/operator.setcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetColor extends Operator.SetColorOperator
```

Represents class for sc operator (set color for non-stroknig operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColor()](#SetColor--) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetColor() {#SetColor--}
```
public SetColor()
```


Initializes operator.

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by the operator.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Operator color.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

