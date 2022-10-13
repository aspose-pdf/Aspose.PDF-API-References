---
title: XslFoLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing XSL-FO file into pdf document.
type: docs
weight: 347
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
## Fields

| Field | Description |
| --- | --- |
| [ParsingErrorsHandlingType](#ParsingErrorsHandlingType) | Source XSLFO document can contain formatting errors. |
## Methods

| Method | Description |
| --- | --- |
| [getBasePath()](#getBasePath--) | The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) |  |
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

### ParsingErrorsHandlingType {#ParsingErrorsHandlingType}
```
public int ParsingErrorsHandlingType
```


Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors

### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file.

**Returns:**
java.lang.String - String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public void setBasePath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

