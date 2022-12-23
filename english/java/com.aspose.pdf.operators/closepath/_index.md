---
title: ClosePath
second_title: Aspose.PDF for Java API Reference
description: Class representing h operator close path.
type: docs
weight: 19
url: /java/com.aspose.pdf.operators/closepath/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ClosePath extends Operator
```

Class representing h operator (close path).
## Constructors

| Constructor | Description |
| --- | --- |
| [ClosePath()](#ClosePath--) | Initializes operator. |
| [ClosePath(int index, ICommand command)](#ClosePath-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getCommandName()](#getCommandName--) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### ClosePath() {#ClosePath--}
```
public ClosePath()
```


Initializes operator.

### ClosePath(int index, ICommand command) {#ClosePath-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ClosePath(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets operator name.

**Returns:**
java.lang.String
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

