---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for Java API Reference
description: If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of.
type: docs
weight: 2100
url: /java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page's markup during conversion of PDF to HTML

## Methods

| Method | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Set by converter. Represents saved HTML as stream |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file. |
| [getSupposedFileName](#getSupposedFileName--) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself |
| [setContentStream](#setContentStream-java.io.InputStream-) | Set by converter. Represents saved HTML as stream |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Set by converter. Represents saved HTML as stream

**Returns:**
InputStream instance

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document.

**Returns:**
int value

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

**Returns:**
int value

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

**Returns:**
String value

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself

**Returns:**
boolean value

### setContentStream {#setContentStream-java.io.InputStream-}
Set by converter. Represents saved HTML as stream

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProcessingCancelled |  | boolean value |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber |  | int value |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber |  | int value |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content
