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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getPropertiesDictionary()](#getPropertiesDictionary--) | Gets properties dictionary |
| [getPropertiesName()](#getPropertiesName--) | Gets properties name |
| [getTag()](#getTag--) | Gets marked content tag |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | For internal usage only |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [setPropertiesDictionary(IPdfDictionary value)](#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-) | Sets properties dictionary |
| [setPropertiesName(IPdfName value)](#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-) | Sets properties name |
| [setTag(String value)](#setTag-java.lang.String-) | Sets marked content tag |
| [toString()](#toString--) | Returns text representation of operator. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


Gets command

**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) - ICommand object
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets operator name.

**Returns:**
java.lang.String - String value
### getIndex() {#getIndex--}
```
public int getIndex()
```


Get Operator index in page operators list.

**Returns:**
int - int value
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Gets array of operator parameters.

**Returns:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - ArrayList of CommandParameter value
### getPropertiesDictionary() {#getPropertiesDictionary--}
```
public IPdfDictionary getPropertiesDictionary()
```


Gets properties dictionary

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary value
### getPropertiesName() {#getPropertiesName--}
```
public IPdfName getPropertiesName()
```


Gets properties name

**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname) - IPdfName value
### getTag() {#getTag--}
```
public String getTag()
```


Gets marked content tag

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


For internal usage only

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Set Operator index in page operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPropertiesDictionary(IPdfDictionary value) {#setPropertiesDictionary-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setPropertiesDictionary(IPdfDictionary value)
```


Sets properties dictionary

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | IPdfDictionary value |

### setPropertiesName(IPdfName value) {#setPropertiesName-com.aspose.pdf.engine.data.IPdfName-}
```
public void setPropertiesName(IPdfName value)
```


Sets properties name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPdfName](../../com.aspose.pdf.engine.data/ipdfname) | IPdfName value |

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
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

