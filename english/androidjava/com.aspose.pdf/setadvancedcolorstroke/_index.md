---
title: Operator.SetAdvancedColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing SCN operator set color for stroking operations.
type: docs
weight: 52
url: /java/com.aspose.pdf/operator.setadvancedcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetAdvancedColorStroke extends Operator.SetColorOperator
```

Class representing SCN operator (set color for stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetAdvancedColorStroke()](#SetAdvancedColorStroke--) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetAdvancedColorStroke() {#SetAdvancedColorStroke--}
```
public SetAdvancedColorStroke()
```


Initializes operator.

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by operator.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Color specifid by operator.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

