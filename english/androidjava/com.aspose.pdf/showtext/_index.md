---
title: Operator.ShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing Tj operator show text.
type: docs
weight: 83
url: /java/com.aspose.pdf/operator.showtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.TextOperator](../../com.aspose.pdf/textoperator), [com.aspose.pdf.Operator.TextShowOperator](../../com.aspose.pdf/textshowoperator)
```
public static class Operator.ShowText extends Operator.TextShowOperator
```

Class representing Tj operator (show text).
## Constructors

| Constructor | Description |
| --- | --- |
| [ShowText(int index, ICommand command)](#ShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ShowText(int index, String text)](#ShowText-int-java.lang.String-) | Constructor of Tj opearor. |
| [ShowText(String text)](#ShowText-java.lang.String-) | Constructor for writing program. |
| [ShowText(String text, Font font)](#ShowText-java.lang.String-com.aspose.pdf.Font-) |  |
| [ShowText()](#ShowText--) | Constructor of Tj operator. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Text of operator. |
| [setText(String value)](#setText-java.lang.String-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
### ShowText(int index, ICommand command) {#ShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ShowText(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ShowText(int index, String text) {#ShowText-int-java.lang.String-}
```
public ShowText(int index, String text)
```


Constructor of Tj opearor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator in operators list. |
| text | java.lang.String | argument of the operator. |

### ShowText(String text) {#ShowText-java.lang.String-}
```
public ShowText(String text)
```


Constructor for writing program.

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


Constructor of Tj operator.

### getText() {#getText--}
```
public String getText()
```


Text of operator.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
