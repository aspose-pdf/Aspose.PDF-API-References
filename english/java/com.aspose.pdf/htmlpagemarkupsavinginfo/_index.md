---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for Java API Reference
description: If SplitToPages property of HtmlSaveOptions then several HTML-files one HTML file per converted page are created during conversion of PDF to HTML.
type: docs
weight: 20
url: /java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object
```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo
```

If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page's markup during conversion of PDF to HTML
## Methods

| Method | Description |
| --- | --- |
| [getSupposedFileName()](#getSupposedFileName--) | Set by converter. |
| [setSupposedFileName(String supposedFileName)](#setSupposedFileName-java.lang.String-) | Set by converter. |
| [getContentStream()](#getContentStream--) | Set by converter. |
| [setContentStream(InputStream contentStream)](#setContentStream-java.io.InputStream-) | Set by converter. |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | Set by converter. |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | Set by converter. |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | Set by converter. |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | Set by converter. |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | Should be set in custom code when necessary. |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | Should be set in custom code when necessary. |
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Returns:**
java.lang.String - String value
### setSupposedFileName(String supposedFileName) {#setSupposedFileName-java.lang.String-}
```
public void setSupposedFileName(String supposedFileName)
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| supposedFileName | java.lang.String | String value |

### getContentStream() {#getContentStream--}
```
public InputStream getContentStream()
```


Set by converter. Represents saved HTML as stream

**Returns:**
java.io.InputStream - InputStream instance
### setContentStream(InputStream contentStream) {#setContentStream-java.io.InputStream-}
```
public void setContentStream(InputStream contentStream)
```


Set by converter. Represents saved HTML as stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | InputStream instance |

### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

**Returns:**
int - int value
### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber | int | int value |

### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document.

**Returns:**
int - int value
### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber | int | int value |

### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself

**Returns:**
boolean - boolean value
### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProcessingCancelled | boolean | boolean value |

