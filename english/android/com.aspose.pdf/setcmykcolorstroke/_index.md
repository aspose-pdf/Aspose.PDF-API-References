---
title: Operator.SetCMYKColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing K operator set CMYK color for stroking operations.
type: docs
weight: 54
url: /java/com.aspose.pdf/operator.setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetCMYKColorStroke extends Operator.SetColorOperator
```

Class representing K operator (set CMYK color for stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCMYKColorStroke(double c, double m, double y, double k)](#SetCMYKColorStroke-double-double-double-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetCMYKColorStroke(double c, double m, double y, double k) {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
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


Returns color

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - 
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

