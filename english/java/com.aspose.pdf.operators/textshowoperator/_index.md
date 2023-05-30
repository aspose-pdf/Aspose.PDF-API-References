---
title: TextShowOperator
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for all operators which used to out text Tj TJ etc.
type: docs
weight: 92
url: /java/com.aspose.pdf.operators/textshowoperator/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator)
```
public class TextShowOperator extends TextOperator
```

Abstract base class for all operators which used to out text (Tj, TJ, etc).
## Constructors

| Constructor | Description |
| --- | --- |
| [TextShowOperator(int index, ICommand command)](#TextShowOperator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [TextShowOperator()](#TextShowOperator--) | Constructor for new TextShowOperator. |
| [TextShowOperator(TextProperties textProperties)](#TextShowOperator-com.aspose.pdf.facades.TextProperties-) | Constructor for TextShowOperator which allows to pass TextProperties. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets text which operator out on the page. |
| [setText(String value)](#setText-java.lang.String-) | Sets text which operator out on the page. |
### TextShowOperator(int index, ICommand command) {#TextShowOperator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public TextShowOperator(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### TextShowOperator() {#TextShowOperator--}
```
public TextShowOperator()
```


Constructor for new TextShowOperator.

### TextShowOperator(TextProperties textProperties) {#TextShowOperator-com.aspose.pdf.facades.TextProperties-}
```
public TextShowOperator(TextProperties textProperties)
```


Constructor for TextShowOperator which allows to pass TextProperties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textProperties | [TextProperties](../../com.aspose.pdf.facades/textproperties) | Text properties. |

### getText() {#getText--}
```
public String getText()
```


Gets text which operator out on the page.

**Returns:**
java.lang.String - String value
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets text which operator out on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

