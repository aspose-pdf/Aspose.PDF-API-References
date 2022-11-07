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
## Fields

| Field | Description |
| --- | --- |
| [SupposedFileName](#SupposedFileName) | Set by converter. |
| [ContentStream](#ContentStream) | Set by converter. |
| [PdfHostPageNumber](#PdfHostPageNumber) | Set by converter. |
| [HtmlHostPageNumber](#HtmlHostPageNumber) | Set by converter. |
| [CustomProcessingCancelled](#CustomProcessingCancelled) | Should be set in custom code when necessary. |
### SupposedFileName {#SupposedFileName}
```
public String SupposedFileName
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

### ContentStream {#ContentStream}
```
public System.IO.Stream ContentStream
```


Set by converter. Represents saved HTML as stream

### PdfHostPageNumber {#PdfHostPageNumber}
```
public int PdfHostPageNumber
```


Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

### HtmlHostPageNumber {#HtmlHostPageNumber}
```
public int HtmlHostPageNumber
```


Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document.

### CustomProcessingCancelled {#CustomProcessingCancelled}
```
public boolean CustomProcessingCancelled
```


Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself

