---
title: ClosePathEOFillStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing b operator close fill and stroke path using even-odd rule.
type: docs
weight: 20
url: /java/com.aspose.pdf.operators/closepatheofillstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ClosePathEOFillStroke extends Operator
```

Class representing b\* operator (close, fill and stroke path using even-odd rule).
## Constructors

| Constructor | Description |
| --- | --- |
| [ClosePathEOFillStroke()](#ClosePathEOFillStroke--) | Initializes operator. |
| [ClosePathEOFillStroke(int index, ICommand command)](#ClosePathEOFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [getCommandName()](#getCommandName--) | Returns text representation of operator. |
### ClosePathEOFillStroke() {#ClosePathEOFillStroke--}
```
public ClosePathEOFillStroke()
```


Initializes operator.

### ClosePathEOFillStroke(int index, ICommand command) {#ClosePathEOFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ClosePathEOFillStroke(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

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


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
