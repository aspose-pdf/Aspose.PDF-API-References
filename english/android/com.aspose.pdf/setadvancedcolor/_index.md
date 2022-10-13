---
title: Operator.SetAdvancedColor
second_title: Aspose.PDF for Java API Reference
description: Class representing scn operator set color for non-stroking operations.
type: docs
weight: 51
url: /java/com.aspose.pdf/operator.setadvancedcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetAdvancedColor extends Operator.SetColorOperator
```

Class representing scn operator (set color for non-stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetAdvancedColor()](#SetAdvancedColor--) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Retuns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetAdvancedColor() {#SetAdvancedColor--}
```
public SetAdvancedColor()
```


Initializes operator.

### getColor() {#getColor--}
```
public Color getColor()
```


Retuns color specified by operator.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Color set by operator.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

