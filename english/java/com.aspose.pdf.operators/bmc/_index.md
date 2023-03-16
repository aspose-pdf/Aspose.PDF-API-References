---
title: BMC
second_title: Aspose.PDF for Java API Reference
description: Class representing BMC operator Begin marked-content sequence.
type: docs
weight: 12
url: /java/com.aspose.pdf.operators/bmc/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class BMC extends Operator
```

Class representing BMC operator (Begin marked-content sequence).
## Constructors

| Constructor | Description |
| --- | --- |
| [BMC(String tag)](#BMC-java.lang.String-) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [getTag()](#getTag--) | Gets marked content tag |
| [setTag(String value)](#setTag-java.lang.String-) | Sets marked content tag |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [toCommand()](#toCommand--) |  |
### BMC(String tag) {#BMC-java.lang.String-}
```
public BMC(String tag)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | Marked content tag. |

### getTag() {#getTag--}
```
public String getTag()
```


Gets marked content tag

**Returns:**
java.lang.String - String value
### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


Sets marked content tag

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
