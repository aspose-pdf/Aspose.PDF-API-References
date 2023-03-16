---
title: Operator
second_title: Aspose.PDF for Java API Reference
description: Abstract class representing operator.
type: docs
weight: 230
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
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
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
