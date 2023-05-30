---
title: SetSpacingMoveToNextLineShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing  operator set word and character spacing move to the next line and show text.
type: docs
weight: 81
url: /java/com.aspose.pdf.operators/setspacingmovetonextlineshowtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextShowOperator](../../com.aspose.pdf.operators/textshowoperator)
```
public class SetSpacingMoveToNextLineShowText extends TextShowOperator
```

Class representing " operator (set word and character spacing, move to the next line and show text).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetSpacingMoveToNextLineShowText(int index, ICommand command)](#SetSpacingMoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetSpacingMoveToNextLineShowText(double aw, double ac, String text)](#SetSpacingMoveToNextLineShowText-double-double-java.lang.String-) | Initializes operator. |
| [SetSpacingMoveToNextLineShowText()](#SetSpacingMoveToNextLineShowText--) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getAw()](#getAw--) | Gets word spacing. |
| [getAc()](#getAc--) | Get character spacing. |
| [getText()](#getText--) | Gets text of operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetSpacingMoveToNextLineShowText(int index, ICommand command) {#SetSpacingMoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetSpacingMoveToNextLineShowText(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetSpacingMoveToNextLineShowText(double aw, double ac, String text) {#SetSpacingMoveToNextLineShowText-double-double-java.lang.String-}
```
public SetSpacingMoveToNextLineShowText(double aw, double ac, String text)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aw | double | double value Word spacing. |
| ac | double | double value Character spacing. |
| text | java.lang.String | string Text value. |

### SetSpacingMoveToNextLineShowText() {#SetSpacingMoveToNextLineShowText--}
```
public SetSpacingMoveToNextLineShowText()
```


Initializes operator.

### getAw() {#getAw--}
```
public double getAw()
```


Gets word spacing.

**Returns:**
double - double value
### getAc() {#getAc--}
```
public double getAc()
```


Get character spacing.

**Returns:**
double - double value
### getText() {#getText--}
```
public String getText()
```


Gets text of operator.

**Returns:**
java.lang.String - String value
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

