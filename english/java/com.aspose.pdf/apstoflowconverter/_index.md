---
title: ApsToFlowConverter
second_title: Aspose.PDF for Java API Reference
description: APS to Flow Conversion
type: docs
weight: 27
url: /java/com.aspose.pdf/apstoflowconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.foundation.rendering.ApsDocumentVisitor
```
public class ApsToFlowConverter extends ApsDocumentVisitor
```

APS to Flow Conversion \* !!! Don't port from C\# as could be ahead of .Net version !!!!
## Constructors

| Constructor | Description |
| --- | --- |
| [ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options)](#ApsToFlowConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [visitPageStart(ApsPage page)](#visitPageStart-com.aspose.foundation.rendering.ApsPage-) |  |
| [visitPageEnd(ApsPage page)](#visitPageEnd-com.aspose.foundation.rendering.ApsPage-) |  |
| [render(ApsNode node)](#render-com.aspose.foundation.rendering.ApsNode-) | Renders a layout node and all its contents into a Excel document. |
| [visitGlyphs(ApsGlyphs glyphs)](#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-) | Visits the glyphs. |
| [visitPathStart(ApsPath path)](#visitPathStart-com.aspose.foundation.rendering.ApsPath-) |  |
| [visitPathEnd(ApsPath path)](#visitPathEnd-com.aspose.foundation.rendering.ApsPath-) |  |
| [visitPathFigureEnd(ApsPathFigure pathFigure)](#visitPathFigureEnd-com.aspose.foundation.rendering.ApsPathFigure-) |  |
| [visitPathFigureStart(ApsPathFigure pathFigure)](#visitPathFigureStart-com.aspose.foundation.rendering.ApsPathFigure-) |  |
| [visitPolyLineSegment(ApsPolyLineSegment segment)](#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-) |  |
| [visitBezierSegment(ApsBezierSegment segment)](#visitBezierSegment-com.aspose.foundation.rendering.ApsBezierSegment-) |  |
| [visitImage(ApsImage image)](#visitImage-com.aspose.foundation.rendering.ApsImage-) | Visits the image. |
| [saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)](#saveDocument-com.aspose.pdf.flow.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-) |  |
### ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options) {#ApsToFlowConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-}
```
public ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | com.aspose.foundation.DocumentInfo |  |
| options | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |

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

### visitPathStart(ApsPath path) {#visitPathStart-com.aspose.foundation.rendering.ApsPath-}
```
public void visitPathStart(ApsPath path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | com.aspose.foundation.rendering.ApsPath |  |

### visitPathEnd(ApsPath path) {#visitPathEnd-com.aspose.foundation.rendering.ApsPath-}
```
public void visitPathEnd(ApsPath path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | com.aspose.foundation.rendering.ApsPath |  |

### visitPathFigureEnd(ApsPathFigure pathFigure) {#visitPathFigureEnd-com.aspose.foundation.rendering.ApsPathFigure-}
```
public void visitPathFigureEnd(ApsPathFigure pathFigure)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pathFigure | com.aspose.foundation.rendering.ApsPathFigure |  |

### visitPathFigureStart(ApsPathFigure pathFigure) {#visitPathFigureStart-com.aspose.foundation.rendering.ApsPathFigure-}
```
public void visitPathFigureStart(ApsPathFigure pathFigure)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pathFigure | com.aspose.foundation.rendering.ApsPathFigure |  |

### visitPolyLineSegment(ApsPolyLineSegment segment) {#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-}
```
public void visitPolyLineSegment(ApsPolyLineSegment segment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsPolyLineSegment |  |

### visitBezierSegment(ApsBezierSegment segment) {#visitBezierSegment-com.aspose.foundation.rendering.ApsBezierSegment-}
```
public void visitBezierSegment(ApsBezierSegment segment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsBezierSegment |  |

### visitImage(ApsImage image) {#visitImage-com.aspose.foundation.rendering.ApsImage-}
```
public void visitImage(ApsImage image)
```


Visits the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.foundation.rendering.ApsImage | The image. |

### saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream) {#saveDocument-com.aspose.pdf.flow.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-}
```
public void saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | com.aspose.pdf.flow.OfficeConverterOptions |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

