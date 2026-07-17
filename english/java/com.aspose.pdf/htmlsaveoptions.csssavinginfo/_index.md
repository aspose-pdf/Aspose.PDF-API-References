---
title: HtmlSaveOptions.CssSavingInfo
linktitle: HtmlSaveOptions.CssSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format
type: docs
weight: 2010
url: /java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.CssSavingInfo

```
public static class HtmlSaveOptions.CssSavingInfo extends Object
```

This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format

## Methods

| Method | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Set by converter. Represents binary content of saved CSS |
| [getCssNumber](#getCssNumber--) | Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content |
| [getSupposedURL](#getSupposedURL--) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content |
| [setContentStream](#setContentStream-java.io.InputStream-) | Set by converter. Represents binary content of saved CSS |
| [setCssNumber](#setCssNumber-int-) | Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content |
| [setSupposedURL](#setSupposedURL-java.lang.String-) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Set by converter. Represents binary content of saved CSS

**Returns:**
InputStream instance

### getCssNumber {#getCssNumber--}
```
public int getCssNumber()
```

Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content

**Returns:**
int value

### getSupposedURL {#getSupposedURL--}
```
public String getSupposedURL()
```

Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Returns:**
String value

### setContentStream {#setContentStream-java.io.InputStream-}
Set by converter. Represents binary content of saved CSS

### setCssNumber {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```

Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cssNumber |  | int value |

### setSupposedURL {#setSupposedURL-java.lang.String-}
Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content
