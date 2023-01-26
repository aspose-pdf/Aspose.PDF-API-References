---
title: Operator
second_title: Aspose.PDF for Java API Reference
description: Abstract class representing operator.
type: docs
weight: 235
url: /java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object
```
public abstract class Operator
```

Abstract class representing operator.
## Constructors

| Constructor | Description |
| --- | --- |
| [Operator(int index, ICommand command)](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | For internal usage only! |
## Methods

| Method | Description |
| --- | --- |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getCommand()](#getCommand--) | Gets command |
| [reset()](#reset--) | For internal usage only |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor IOperatorSelector which provides operators processing. |
| [toString()](#toString--) | Translates command and parameters into string representation. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
### Operator(int index, ICommand command) {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Operator(int index, ICommand command)
```


For internal usage only!

Constructor of Operators. Creates operator by command object and operator index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator in operators list |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Command object of operator |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Get Operator index in page operators list.

**Returns:**
int - int value
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Set Operator index in page operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets operator name.

**Returns:**
java.lang.String - String value
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Gets array of operator parameters.

**Returns:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - ArrayList of CommandParameter value
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


Gets command

**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) - ICommand object
### reset() {#reset--}
```
public void reset()
```


For internal usage only

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public abstract void accept(IOperatorSelector visitor)
```


Accepts visitor IOperatorSelector which provides operators processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object |

### toString() {#toString--}
```
public String toString()
```


Translates command and parameters into string representation.

**Returns:**
java.lang.String - Operator text
### toString(IPdfPrimitive primitive) {#toString-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static String toString(IPdfPrimitive primitive)
```


Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primitive | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Primitive |

**Returns:**
java.lang.String - Text represetation of the primitive
### isTextShowOperator(Operator op) {#isTextShowOperator-com.aspose.pdf.Operator-}
```
public static boolean isTextShowOperator(Operator op)
```


Determines if the operator is operator which responsible for text output (Tj, TJ, etc)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

**Returns:**
boolean - True if this is text output operator
