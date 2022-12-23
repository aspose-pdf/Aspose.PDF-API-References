---
title: ShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing Tj operator show text.
type: docs
weight: 86
url: /java/com.aspose.pdf.operators/showtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextShowOperator](../../com.aspose.pdf.operators/textshowoperator)
```
public class ShowText extends TextShowOperator
```

Class representing Tj operator (show text).
## Constructors

| Constructor | Description |
| --- | --- |
| [ShowText(int index, ICommand command)](#ShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Initializes operator. |
| [ShowText(int index, String text)](#ShowText-int-java.lang.String-) | Initializes Tj opearor. |
| [ShowText(String text)](#ShowText-java.lang.String-) | Initializes Tj operator. |
| [ShowText(String text, Font font)](#ShowText-java.lang.String-com.aspose.pdf.Font-) |  |
| [ShowText()](#ShowText--) | Initializes of Tj operator. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets text of operator. |
| [setText(String value)](#setText-java.lang.String-) | Set text of operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
### ShowText(int index, ICommand command) {#ShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ShowText(int index, ICommand command)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ShowText(int index, String text) {#ShowText-int-java.lang.String-}
```
public ShowText(int index, String text)
```


Initializes Tj opearor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator in operators list. |
| text | java.lang.String | argument of the operator. |

### ShowText(String text) {#ShowText-java.lang.String-}
```
public ShowText(String text)
```


Initializes Tj operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | argument of the operator. |

### ShowText(String text, Font font) {#ShowText-java.lang.String-com.aspose.pdf.Font-}
```
public ShowText(String text, Font font)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | [Font](../../com.aspose.pdf/font) |  |

### ShowText() {#ShowText--}
```
public ShowText()
```


Initializes of Tj operator.

### getText() {#getText--}
```
public String getText()
```


Gets text of operator.

**Returns:**
java.lang.String - String value
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Set text of operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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


Produces text code of operator.

**Returns:**
java.lang.String - Text representation of operator.
