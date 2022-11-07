---
title: Operator.DP
second_title: Aspose.PDF for Java API Reference
description: Class represeting DP operator designamte marked content point.
type: docs
weight: 25
url: /java/com.aspose.pdf/operator.dp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.DP extends Operator
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
| [getPropertiesDictionary()](#getPropertiesDictionary--) |  |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [getPropertiesName()](#getPropertiesName--) |  |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) |  |
| [toString()](#toString--) |  |
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
| tag | java.lang.String |  |

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
java.lang.String - 
### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


Sets marked content tag

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPropertiesDictionary() {#getPropertiesDictionary--}
```
public IPdfDictionary getPropertiesDictionary()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### setPropertiesDictionary(IPdfDictionary value) {#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setPropertiesDictionary(IPdfDictionary value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### getPropertiesName() {#getPropertiesName--}
```
public IPdfName getPropertiesName()
```




**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### setPropertiesName(IPdfName value) {#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-}
```
public void setPropertiesName(IPdfName value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) |  |

### toString() {#toString--}
```
public String toString()
```


Translates command and parameters into string representation.

**Returns:**
java.lang.String
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

