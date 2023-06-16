---
title: MoveToNextLine
second_title: Aspose.PDF for Java API Reference
description: Class representing T operator Move to start of the next line.
type: docs
weight: 51
url: /java/com.aspose.pdf.operators/movetonextline/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextPlaceOperator](../../com.aspose.pdf.operators/textplaceoperator)
```
public class MoveToNextLine extends TextPlaceOperator
```

Class representing T\* operator (Move to start of the next line).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveToNextLine(int index, ICommand command)](#MoveToNextLine-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [MoveToNextLine()](#MoveToNextLine--) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text of the operator. |
### MoveToNextLine(int index, ICommand command) {#MoveToNextLine-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public MoveToNextLine(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### MoveToNextLine() {#MoveToNextLine--}
```
public MoveToNextLine()
```


Constructor for writing program.

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


Returns text of the operator.

**Returns:**
java.lang.String - Text representation of operator.
