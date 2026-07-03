---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.
type: docs
weight: 2070
url: /java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.

## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | creates new instance of HtmlImageSavingInfo |

## Methods

| Method | Description |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated. |
| [getImageType](#getImageType--) | Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done |
| [getParentType](#getParentType--) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1' |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated. |
| [setImageType](#setImageType-int-) | Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done |
| [setParentType](#setParentType-int-) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1' |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

creates new instance of HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated.

**Returns:**
int value

### getImageType {#getImageType--}
```
public int getImageType()
```

Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Returns:**
HtmlImageType element @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content).

**Returns:**
ImageParentTypes element @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1'

**Returns:**
int value

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlHostPageNumber |  | int value |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageType |  | HtmlImageType element @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentType |  | ImageParentTypes element @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is unknown, it always return '1'

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfHostPageNumber |  | int value |
