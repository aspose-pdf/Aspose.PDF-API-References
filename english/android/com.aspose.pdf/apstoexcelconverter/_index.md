---
title: ApsToExcelConverter
second_title: Aspose.PDF for Java API Reference
description: APS to Excel Conversion
type: docs
weight: 24
url: /java/com.aspose.pdf/apstoexcelconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.foundation.rendering.ApsDocumentVisitor
```
public class ApsToExcelConverter extends ApsDocumentVisitor
```

APS to Excel Conversion
## Constructors

| Constructor | Description |
| --- | --- |
| [ApsToExcelConverter(DocumentInfo info, ExcelSaveOptions options)](#ApsToExcelConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLines()](#getLines--) |  |
| [getImages()](#getImages--) |  |
| [getTextFragments()](#getTextFragments--) |  |
| [visitPageStart(ApsPage page)](#visitPageStart-com.aspose.foundation.rendering.ApsPage-) |  |
| [visitPageEnd(ApsPage page)](#visitPageEnd-com.aspose.foundation.rendering.ApsPage-) |  |
| [render(ApsNode node)](#render-com.aspose.foundation.rendering.ApsNode-) | Renders a layout node and all its contents into a Excel document. |
| [visitGlyphs(ApsGlyphs glyphs)](#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-) | Visits the glyphs. |
| [visitPolyLineSegment(ApsPolyLineSegment segment)](#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-) |  |
| [visitImage(ApsImage image)](#visitImage-com.aspose.foundation.rendering.ApsImage-) | Visits the image. |
| [saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)](#saveDocument-com.aspose.pdf.office.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-) |  |
### ApsToExcelConverter(DocumentInfo info, ExcelSaveOptions options) {#ApsToExcelConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-}
```
public ApsToExcelConverter(DocumentInfo info, ExcelSaveOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | com.aspose.foundation.DocumentInfo |  |
| options | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |

### getLines() {#getLines--}
```
public System.Collections.Generic.List<String> getLines()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String>
### getImages() {#getImages--}
```
public System.Collections.Generic.List<String> getImages()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String>
### getTextFragments() {#getTextFragments--}
```
public System.Collections.Generic.List<String> getTextFragments()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String>
### visitPageStart(ApsPage page) {#visitPageStart-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageStart(ApsPage page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

### visitPageEnd(ApsPage page) {#visitPageEnd-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageEnd(ApsPage page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

### render(ApsNode node) {#render-com.aspose.foundation.rendering.ApsNode-}
```
public void render(ApsNode node)
```


Renders a layout node and all its contents into a Excel document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | com.aspose.foundation.rendering.ApsNode | The aps node. |

### visitGlyphs(ApsGlyphs glyphs) {#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-}
```
public void visitGlyphs(ApsGlyphs glyphs)
```


Visits the glyphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| glyphs | com.aspose.foundation.rendering.ApsGlyphs | Internal instance |

### visitPolyLineSegment(ApsPolyLineSegment segment) {#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-}
```
public void visitPolyLineSegment(ApsPolyLineSegment segment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsPolyLineSegment |  |

### visitImage(ApsImage image) {#visitImage-com.aspose.foundation.rendering.ApsImage-}
```
public void visitImage(ApsImage image)
```


Visits the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.foundation.rendering.ApsImage | The image. |

### saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream) {#saveDocument-com.aspose.pdf.office.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-}
```
public void saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | com.aspose.pdf.office.OfficeConverterOptions |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

