---
title: Operator.BDC
second_title: Aspose.PDF for Java API Reference
description: class representing BDC operator Begin marked-content sequence
type: docs
weight: 10
url: /java/com.aspose.pdf/operator.bdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.BDC extends Operator
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
| [getPropertiesDictionary()](#getPropertiesDictionary--) |  |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [getPropertiesName()](#getPropertiesName--) |  |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) |  |
| [toString()](#toString--) |  |
| [toCommand()](#toCommand--) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
### BDC(String tag) {#BDC-java.lang.String-}
```
public BDC(String tag)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String |  |

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
