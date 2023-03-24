---
title: BI
second_title: Aspose.PDF for Java API Reference
description: Class representing BI operator Begin inline image obect.
type: docs
weight: 11
url: /java/com.aspose.pdf.operators/bi/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class BI extends Operator
```

Class representing BI operator (Begin inline image obect).
## Constructors

| Constructor | Description |
| --- | --- |
| [BI()](#BI--) | Initializes operator. |
| [BI(int index, ICommand command)](#BI-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toCommand()](#toCommand--) |  |
### BI() {#BI--}
```
public BI()
```


Initializes operator.

### BI(int index, ICommand command) {#BI-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public BI(int index, ICommand command)
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

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
