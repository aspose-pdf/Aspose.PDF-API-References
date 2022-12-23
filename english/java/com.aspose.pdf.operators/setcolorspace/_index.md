---
title: SetColorSpace
second_title: Aspose.PDF for Java API Reference
description: Class representing cs operator set colorspace for non-stroking operations
type: docs
weight: 64
url: /java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetColorSpace extends Operator
```

Class representing cs operator (set colorspace for non-stroking operations)
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorSpace(String name)](#SetColorSpace-java.lang.String-) | Initializes operator. |
| [SetColorSpace(int index, ICommand command)](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets color space name. |
| [setName(String value)](#setName-java.lang.String-) | Sets color space name. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getCommandName()](#getCommandName--) | Gets command name. |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [toCommand()](#toCommand--) |  |
### SetColorSpace(String name) {#SetColorSpace-java.lang.String-}
```
public SetColorSpace(String name)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Color space name. |

### SetColorSpace(int index, ICommand command) {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColorSpace(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getName() {#getName--}
```
public String getName()
```


Gets color space name.

**Returns:**
java.lang.String - String value
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets color space name.

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

### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets command name.

**Returns:**
java.lang.String - String value
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
