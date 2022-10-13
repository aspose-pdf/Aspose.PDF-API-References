---
title: HtmlSaveOptions.CssSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format
type: docs
weight: 11
url: /java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object
```
public static class HtmlSaveOptions.CssSavingInfo
```

This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format
## Methods

| Method | Description |
| --- | --- |
| [getCssNumber()](#getCssNumber--) | Set by converter. |
| [setCssNumber(int cssNumber)](#setCssNumber-int-) | Set by converter. |
| [getSupposedURL()](#getSupposedURL--) | Set by converter. |
| [setSupposedURL(String supposedURL)](#setSupposedURL-java.lang.String-) | Set by converter. |
| [getContentStream()](#getContentStream--) | Set by converter. |
| [setContentStream(InputStream contentStream)](#setContentStream-java.io.InputStream-) | Set by converter. |
### getCssNumber() {#getCssNumber--}
```
public int getCssNumber()
```


Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content

**Returns:**
int - int value
### setCssNumber(int cssNumber) {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```


Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cssNumber | int | int value |

### getSupposedURL() {#getSupposedURL--}
```
public String getSupposedURL()
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Returns:**
java.lang.String - String value
### setSupposedURL(String supposedURL) {#setSupposedURL-java.lang.String-}
```
public void setSupposedURL(String supposedURL)
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| supposedURL | java.lang.String | String value |

### getContentStream() {#getContentStream--}
```
public InputStream getContentStream()
```


Set by converter. Represents binary content of saved CSS

**Returns:**
java.io.InputStream - InputStream instance
### setContentStream(InputStream contentStream) {#setContentStream-java.io.InputStream-}
```
public void setContentStream(InputStream contentStream)
```


Set by converter. Represents binary content of saved CSS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | InputStream instance |

