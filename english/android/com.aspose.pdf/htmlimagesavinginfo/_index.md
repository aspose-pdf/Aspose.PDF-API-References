---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource image files saving during PDF to HTML conversion.
type: docs
weight: 17
url: /java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlImageSavingInfo()](#HtmlImageSavingInfo--) | creates new instance of HtmlImageSavingInfo |
## Fields

| Field | Description |
| --- | --- |
| [ImageType](#ImageType) | Represents type of saved image referenced in HTML. |
| [ParentType](#ParentType) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. |
| [PdfHostPageNumber](#PdfHostPageNumber) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. |
| [HtmlHostPageNumber](#HtmlHostPageNumber) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. |
### HtmlImageSavingInfo() {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```


creates new instance of HtmlImageSavingInfo

### ImageType {#ImageType}
```
public int ImageType
```


Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

### ParentType {#ParentType}
```
public int ParentType
```


Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content).

### PdfHostPageNumber {#PdfHostPageNumber}
```
public int PdfHostPageNumber
```


Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1'

### HtmlHostPageNumber {#HtmlHostPageNumber}
```
public int HtmlHostPageNumber
```


Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated.

