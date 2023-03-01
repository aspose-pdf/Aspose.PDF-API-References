---
title: BT
second_title: Aspose.PDF for Java API Reference
description: Class representing BT operator Begin of text block.
type: docs
weight: 13
url: /java/com.aspose.pdf.operators/bt/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.BlockTextOperator](../../com.aspose.pdf.operators/blocktextoperator)
```
public class BT extends BlockTextOperator
```

Class representing BT operator (Begin of text block).
## Constructors

| Constructor | Description |
| --- | --- |
| [BT()](#BT--) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
| [toCommand()](#toCommand--) |  |
### BT() {#BT--}
```
public BT()
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


Produces text code of operator.

**Returns:**
java.lang.String - Text representation of operator.
### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
