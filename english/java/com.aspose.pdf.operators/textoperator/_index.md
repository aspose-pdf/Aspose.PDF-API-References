---
title: TextOperator
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for text-related operators TJ Tj Tm BT ET etc.
type: docs
weight: 90
url: /java/com.aspose.pdf.operators/textoperator/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public abstract class TextOperator extends Operator
```

Abstract base class for text-related operators (TJ, Tj, Tm, BT, ET, etc).
## Constructors

| Constructor | Description |
| --- | --- |
| [TextOperator()](#TextOperator--) | Constructor for new operator. |
| [TextOperator(TextProperties textProperties)](#TextOperator-com.aspose.pdf.facades.TextProperties-) | Text operator which accepts text properties. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### TextOperator() {#TextOperator--}
```
public TextOperator()
```


Constructor for new operator.

### TextOperator(TextProperties textProperties) {#TextOperator-com.aspose.pdf.facades.TextProperties-}
```
public TextOperator(TextProperties textProperties)
```


Text operator which accepts text properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textProperties | [TextProperties](../../com.aspose.pdf.facades/textproperties) | Text properties. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

