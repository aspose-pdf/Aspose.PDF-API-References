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
| [BDC(int index, ICommand command)](#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [BDC(String tag, IPdfDictionary properties)](#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [BDC(String tag, IPdfName property)](#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfName-) |  |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getTag()](#getTag--) | Gets marked content tag |
| [setTag(String value)](#setTag-java.lang.String-) | Sets marked content tag |
| [getPropertiesDictionary()](#getPropertiesDictionary--) | Gets properties dictionary |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) | Sets properties dictionary |
| [getPropertiesName()](#getPropertiesName--) | Gets properties name |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) | Sets properties name |
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

### BDC(int index, ICommand command) {#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public BDC(int index, ICommand command)
```


Constructor for operator class. Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### BDC(String tag, IPdfDictionary properties) {#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public BDC(String tag, IPdfDictionary properties)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String |  |
| properties | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### BDC(String tag, IPdfName property) {#BDC-java.lang.String-com.aspose.pdf.engine.data.IPdfName-}
```
public BDC(String tag, IPdfName property)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String |  |
| property | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) |  |

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

### getPropertiesDictionary() {#getPropertiesDictionary--}
```
public IPdfDictionary getPropertiesDictionary()
```


Gets properties dictionary

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary value
### setPropertiesDictionary(IPdfDictionary value) {#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setPropertiesDictionary(IPdfDictionary value)
```


Sets properties dictionary

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | IPdfDictionary value |

### getPropertiesName() {#getPropertiesName--}
```
public IPdfName getPropertiesName()
```


Gets properties name

**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname) - IPdfName value
### setPropertiesName(IPdfName value) {#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-}
```
public void setPropertiesName(IPdfName value)
```


Sets properties name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) | IPdfName value |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
