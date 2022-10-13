---
title: Operator.SetCMYKColor
second_title: Aspose.PDF for Java API Reference
description: Class representing k operator set CMYK color for non-stroknig operations.
type: docs
weight: 53
url: /java/com.aspose.pdf/operator.setcmykcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetCMYKColor extends Operator.SetColorOperator
```

Class representing k operator (set CMYK color for non-stroknig operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCMYKColor(double c, double m, double y, double k)](#SetCMYKColor-double-double-double-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetCMYKColor(double c, double m, double y, double k) {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double |  |
| m | double |  |
| y | double |  |
| k | double |  |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Color.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

