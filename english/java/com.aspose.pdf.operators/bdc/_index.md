---
title: BDC
second_title: Aspose.PDF for Java API Reference
description: class representing BDC operator Begin marked-content sequence
type: docs
weight: 10
url: /java/com.aspose.pdf.operators/bdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class BDC extends Operator
```

class representing BDC operator (Begin marked-content sequence)
## Constructors

| Constructor | Description |
| --- | --- |
| [BDC(String tag)](#BDC-java.lang.String-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getTag()](#getTag--) | Gets marked content tag |
| [setTag(String value)](#setTag-java.lang.String-) | Sets marked content tag |
| [getPropertiesDictionary()](#getPropertiesDictionary--) | Gets properties dictionary |
| [getPropertiesName()](#getPropertiesName--) | Gets properties name |
| [toString()](#toString--) | Returns text representation of operator. |
### BDC(String tag) {#BDC-java.lang.String-}
```
public BDC(String tag)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | String Tag value |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

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

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
