---
title: XmlLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing XML file into pdf document.
type: docs
weight: 333
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
| [XmlLoadOptions(InputStream xslStream)](#XmlLoadOptions-java.io.InputStream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getXslStream()](#getXslStream--) |  |
| [close()](#close--) |  |
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
| xslFile | java.lang.String | Xsl file to convert xml document into pdf document. |

### XmlLoadOptions(InputStream xslStream) {#XmlLoadOptions-java.io.InputStream-}
```
public XmlLoadOptions(InputStream xslStream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xslStream | java.io.InputStream |  |

### getXslStream() {#getXslStream--}
```
public InputStream getXslStream()
```




**Returns:**
java.io.InputStream
### close() {#close--}
```
public void close()
```



