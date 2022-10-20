---
title: ET
second_title: Aspose.PDF for Java API Reference
description: Class representing operator ET End of text block.
type: docs
weight: 34
url: /java/com.aspose.pdf.operators/et/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.BlockTextOperator](../../com.aspose.pdf.operators/blocktextoperator)
```
public class ET extends BlockTextOperator
```

Class representing operator ET (End of text block).
## Constructors

| Constructor | Description |
| --- | --- |
| [ET(int index, ICommand command)](#ET-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ET()](#ET--) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
### ET(int index, ICommand command) {#ET-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ET(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ET() {#ET--}
```
public ET()
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
