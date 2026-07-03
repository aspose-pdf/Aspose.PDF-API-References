---
title: Operator
second_title: Aspose.PDF for Java API Reference
description: Abstract class representing operator.
type: docs
weight: 3180
url: /java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Abstract class representing operator.

## Constructors

| Constructor | Description |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | For internal usage only! |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor IOperatorSelector which provides operators processing. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Creates operator by name of com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand instance. |
| [equals](#equals-com.aspose.pdf.Operator-) | Compares this instance with the given object. |
| [getCommand](#getCommand--) | Gets command |
| [getCommandName](#getCommandName--) | Gets operator name. |
| [getIndex](#getIndex--) | Get Operator index in page operators list. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [setIndex](#setIndex-int-) | Set Operator index in page operators list. |
| [toString](#toString--) | Translates command and parameters into string representation. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Compares this instance with the given object. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
For internal usage only!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor IOperatorSelector which provides operators processing.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Creates operator by name of com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand instance.

### equals {#equals-com.aspose.pdf.Operator-}
Compares this instance with the given object.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Gets command

**Returns:**
ICommand object

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Gets operator name.

**Returns:**
String value

### getIndex {#getIndex--}
```
public int getIndex()
```

Get Operator index in page operators list.

**Returns:**
int value

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Determines if the operator is operator which responsible for text output (Tj, TJ, etc)

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Set Operator index in page operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### toString {#toString--}
```
public String toString()
```

Translates command and parameters into string representation.

**Returns:**
Operator text

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Compares this instance with the given object.
