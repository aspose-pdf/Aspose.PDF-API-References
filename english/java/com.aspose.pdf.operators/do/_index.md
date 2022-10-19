---
title: Do
second_title: Aspose.PDF for Java API Reference
description: Class representing Do operator Invoke XObject.
type: docs
weight: 28
url: /java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Do extends Operator
```

Class representing Do operator (Invoke XObject).
## Constructors

| Constructor | Description |
| --- | --- |
| [Do(int index, ICommand command)](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [Do(String name)](#Do-java.lang.String-) | Constructs new Do operator. |
| [Do()](#Do--) | Constructs new Do operator. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Get name of XObject argument of the operator. |
| [setName(String value)](#setName-java.lang.String-) | Set name of XObject argument of the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [getCommandName()](#getCommandName--) | Gets command name |
| [toCommand()](#toCommand--) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
### Do(int index, ICommand command) {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Do(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### Do(String name) {#Do-java.lang.String-}
```
public Do(String name)
```


Constructs new Do operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of invoked XObject. |

### Do() {#Do--}
```
public Do()
```


Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names.

### getName() {#getName--}
```
public String getName()
```


Get name of XObject argument of the operator.

**Returns:**
java.lang.String - String value
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Set name of XObject argument of the operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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


Gets command name

**Returns:**
java.lang.String - String value
### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

