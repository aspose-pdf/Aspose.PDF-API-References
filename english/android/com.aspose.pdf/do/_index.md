---
title: Operator.Do
second_title: Aspose.PDF for Java API Reference
description: Class representing Do operator Invoke XObject.
type: docs
weight: 26
url: /java/com.aspose.pdf/operator.do/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.Do extends Operator
```

Class representing Do operator (Invoke XObject).
## Constructors

| Constructor | Description |
| --- | --- |
| [Do(String name)](#Do-java.lang.String-) | Constructs new Do operator. |
| [Do()](#Do--) | Constructs new Do operator. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of XObject argument of the operator. |
| [setName(String value)](#setName-java.lang.String-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [getCommandName()](#getCommandName--) |  |
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


Name of XObject argument of the operator.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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


Gets operator name.

**Returns:**
java.lang.String
