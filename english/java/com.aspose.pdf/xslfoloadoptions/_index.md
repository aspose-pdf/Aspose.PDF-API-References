---
title: XslFoLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing XSL-FO file into pdf document.
type: docs
weight: 429
url: /java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions), [com.aspose.pdf.XmlLoadOptions](../../com.aspose.pdf/xmlloadoptions)
```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Represents options for loading/importing XSL-FO file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [XslFoLoadOptions()](#XslFoLoadOptions--) | Creates  XslFoLoadOptions  object without xsl data. |
| [XslFoLoadOptions(String xslFile)](#XslFoLoadOptions-java.lang.String-) | Creates  XslFoLoadOptions  object with xsl data. |
| [XslFoLoadOptions(InputStream xslStream)](#XslFoLoadOptions-java.io.InputStream-) | Creates  XslFoLoadOptions  object with xsl data. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Close instance |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file. |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getParsingErrorsHandlingType()](#getParsingErrorsHandlingType--) | Source XSLFO document can contain formatting errors. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [getXslStream()](#getXslStream--) | Gets xsl data for converting xml into pdf document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(String value)](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType(int parsingErrorsHandlingType)](#setParsingErrorsHandlingType-int-) | Source XSLFO document can contain formatting errors. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XslFoLoadOptions() {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```


Creates  XslFoLoadOptions  object without xsl data.

### XslFoLoadOptions(String xslFile) {#XslFoLoadOptions-java.lang.String-}
```
public XslFoLoadOptions(String xslFile)
```


Creates  XslFoLoadOptions  object with xsl data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xslFile | java.lang.String | Xsl file to convert XSL-FO document into pdf document. |

### XslFoLoadOptions(InputStream xslStream) {#XslFoLoadOptions-java.io.InputStream-}
```
public XslFoLoadOptions(InputStream xslStream)
```


Creates  XslFoLoadOptions  object with xsl data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xslStream | java.io.InputStream | Xsl stream to convert XSL-FO document into pdf document. |

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
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file.

**Returns:**
java.lang.String - String
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
### getParsingErrorsHandlingType() {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```


Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors

**Returns:**
int - ParsingErrorsHandlingTypes element
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




### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public void setBasePath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setParsingErrorsHandlingType(int parsingErrorsHandlingType) {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```


Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingErrorsHandlingType | int | ParsingErrorsHandlingTypes element |

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

