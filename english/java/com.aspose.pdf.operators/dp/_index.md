---
title: DP
second_title: Aspose.PDF for Java API Reference
description: Class represeting DP operator designamte marked content point.
type: docs
weight: 27
url: /java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class DP extends Operator
```

Class represeting DP operator (designamte marked content point).
## Constructors

| Constructor | Description |
| --- | --- |
| [DP(String tag)](#DP-java.lang.String-) | Initializes operator. |
| [DP(int index, ICommand command)](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [DP(String tag, IPdfDictionary properties)](#DP-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
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
| [toCommand()](#toCommand--) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
### DP(String tag) {#DP-java.lang.String-}
```
public DP(String tag)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | String Tag value |

### DP(int index, ICommand command) {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public DP(int index, ICommand command)
```


Constructor for operator class. Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### DP(String tag, IPdfDictionary properties) {#DP-java.lang.String-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public DP(String tag, IPdfDictionary properties)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String |  |
| properties | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

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
| value | java.lang.String | String object |

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

