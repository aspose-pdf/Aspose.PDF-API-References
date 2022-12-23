---
title: BX
second_title: Aspose.PDF for Java API Reference
description: Class representing BX operator begin compatibility section.
type: docs
weight: 14
url: /java/com.aspose.pdf.operators/bx/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class BX extends Operator
```

Class representing BX operator (begin compatibility section).
## Constructors

| Constructor | Description |
| --- | --- |
| [BX()](#BX--) | Initializes operator. |
| [BX(int index, ICommand command)](#BX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [getCommandName()](#getCommandName--) | Returns text representation of command name. |
| [toCommand()](#toCommand--) |  |
### BX() {#BX--}
```
public BX()
```


Initializes operator.

### BX(int index, ICommand command) {#BX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public BX(int index, ICommand command)
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


Returns text representation of command name.

**Returns:**
java.lang.String - String value
### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
