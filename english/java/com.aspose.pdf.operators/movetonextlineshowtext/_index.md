---
title: MoveToNextLineShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing  operator move to next line and show text.
type: docs
weight: 50
url: /java/com.aspose.pdf.operators/movetonextlineshowtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextShowOperator](../../com.aspose.pdf.operators/textshowoperator)
```
public class MoveToNextLineShowText extends TextShowOperator
```

Class representing ' operator (move to next line and show text).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveToNextLineShowText()](#MoveToNextLineShowText--) | Initializesoperator. |
| [MoveToNextLineShowText(String text)](#MoveToNextLineShowText-java.lang.String-) | Initializes operator. |
| [MoveToNextLineShowText(int index, ICommand command)](#MoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets operator text. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### MoveToNextLineShowText() {#MoveToNextLineShowText--}
```
public MoveToNextLineShowText()
```


Initializesoperator.

### MoveToNextLineShowText(String text) {#MoveToNextLineShowText-java.lang.String-}
```
public MoveToNextLineShowText(String text)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text. |

### MoveToNextLineShowText(int index, ICommand command) {#MoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public MoveToNextLineShowText(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getText() {#getText--}
```
public String getText()
```


Gets operator text.

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

