---
title: ID
second_title: Aspose.PDF for Java API Reference
description: Class representing ID operator Begin inline image data.
type: docs
weight: 43
url: /java/com.aspose.pdf.operators/id/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ID extends Operator
```

Class representing ID operator (Begin inline image data).
## Constructors

| Constructor | Description |
| --- | --- |
| [ID(int index, ICommand command)](#ID-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getCommandName()](#getCommandName--) |  |
### ID(int index, ICommand command) {#ID-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ID(int index, ICommand command)
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

### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets operator name.

**Returns:**
java.lang.String
