---
title: XslFoLoadOptions
linktitle: XslFoLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing XSL-FO file into pdf document.
type: docs
weight: 5780
url: /java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Represents options for loading/importing XSL-FO file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Creates {@code XslFoLoadOptions} object without xsl data. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Creates {@code XslFoLoadOptions} object without xsl data. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Creates {@code XslFoLoadOptions} object without xsl data. |

## Methods

| Method | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Creates {@code XslFoLoadOptions} object without xsl data.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Creates {@code XslFoLoadOptions} object without xsl data.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Creates {@code XslFoLoadOptions} object without xsl data.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

The base path/url from which are searched relative pathes to external resources (if any) referenced in loaded SVG file.

**Returns:**
String

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors

**Returns:**
ParsingErrorsHandlingTypes element @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes element @see ParsingErrorsHandlingTypes |
