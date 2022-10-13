---
title: Operator.SetSpacingMoveToNextLineShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing  operator set word and character spacing move to the next line and show text.
type: docs
weight: 76
url: /java/com.aspose.pdf/operator.setspacingmovetonextlineshowtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.TextOperator](../../com.aspose.pdf/textoperator), [com.aspose.pdf.Operator.TextShowOperator](../../com.aspose.pdf/textshowoperator)
```
public static class Operator.SetSpacingMoveToNextLineShowText extends Operator.TextShowOperator
```

Class representing " operator (set word and character spacing, move to the next line and show text).
## Methods

| Method | Description |
| --- | --- |
| [getAw()](#getAw--) | Gets word spacing. |
| [getAc()](#getAc--) | Get character spacing. |
| [getText()](#getText--) | Gets text of operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### getAw() {#getAw--}
```
public double getAw()
```


Gets word spacing.

**Returns:**
double
### getAc() {#getAc--}
```
public double getAc()
```


Get character spacing.

**Returns:**
double
### getText() {#getText--}
```
public String getText()
```


Gets text of operator.

**Returns:**
java.lang.String
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

