---
title: XmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing XML file into pdf document.
type: docs
weight: 415
url: /java/com.aspose.pdf/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public class XmlLoadOptions extends LoadOptions
```

Represents options for loading/importing XML file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Creates  XmlLoadOptions  object without xsl data. |
| [XmlLoadOptions(String xslFile)](#XmlLoadOptions-java.lang.String-) | Creates  XmlLoadOptions  object with xsl data. |
| [XmlLoadOptions(InputStream xslStream)](#XmlLoadOptions-java.io.InputStream-) | Creates  XmlLoadOptions  object with xsl data. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Close instance |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [getXslStream()](#getXslStream--) | Gets xsl data for converting xml into pdf document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Creates  XmlLoadOptions  object without xsl data.

### XmlLoadOptions(String xslFile) {#XmlLoadOptions-java.lang.String-}
```
public XmlLoadOptions(String xslFile)
```


Creates  XmlLoadOptions  object with xsl data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xslFile | java.lang.String | String Xsl file to convert xml document into pdf document. |

### XmlLoadOptions(InputStream xslStream) {#XmlLoadOptions-java.io.InputStream-}
```
public XmlLoadOptions(InputStream xslStream)
```


Creates  XmlLoadOptions  object with xsl data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xslStream | java.io.InputStream | InputStream Xsl stream to convert xml document into pdf document. |

### close() {#close--}
```
public void close()
```


Close instance

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
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### getXslStream() {#getXslStream--}
```
public InputStream getXslStream()
```


Gets xsl data for converting xml into pdf document.

**Returns:**
java.io.InputStream - InputStream
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

