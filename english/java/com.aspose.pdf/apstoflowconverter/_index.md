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
| [dispose()](#dispose--) |  |
| [endVisitGroup(ApsGroup arg0)](#endVisitGroup-com.aspose.foundation.rendering.ApsGroup-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [render(ApsNode node)](#render-com.aspose.foundation.rendering.ApsNode-) | Renders a layout node and all its contents into a Excel document. |
| [saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)](#saveDocument-com.aspose.pdf.flow.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [visitBezierSegment(ApsBezierSegment segment)](#visitBezierSegment-com.aspose.foundation.rendering.ApsBezierSegment-) |  |
| [visitBookmark(ApsBookmark arg0)](#visitBookmark-com.aspose.foundation.rendering.ApsBookmark-) |  |
| [visitCanvasEnd(ApsCanvas arg0)](#visitCanvasEnd-com.aspose.foundation.rendering.ApsCanvas-) |  |
| [visitCanvasStart(ApsCanvas arg0)](#visitCanvasStart-com.aspose.foundation.rendering.ApsCanvas-) |  |
| [visitFormComboBox(ApsComboBox arg0)](#visitFormComboBox-com.aspose.foundation.rendering.ApsComboBox-) |  |
| [visitFormFieldButton(ApsButton arg0)](#visitFormFieldButton-com.aspose.foundation.rendering.ApsButton-) |  |
| [visitFormFieldCheckbox(ApsCheckBox arg0)](#visitFormFieldCheckbox-com.aspose.foundation.rendering.ApsCheckBox-) |  |
| [visitFormFieldRadioButton(ApsRadioButton arg0)](#visitFormFieldRadioButton-com.aspose.foundation.rendering.ApsRadioButton-) |  |
| [visitFormFieldText(ApsTextField arg0)](#visitFormFieldText-com.aspose.foundation.rendering.ApsTextField-) |  |
| [visitGlyphs(ApsGlyphs glyphs)](#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-) | Visits the glyphs. |
| [visitGroup(ApsGroup arg0)](#visitGroup-com.aspose.foundation.rendering.ApsGroup-) |  |
| [visitImage(ApsImage image)](#visitImage-com.aspose.foundation.rendering.ApsImage-) | Visits the image. |
| [visitOutlineItem(ApsOutlineItem arg0)](#visitOutlineItem-com.aspose.foundation.rendering.ApsOutlineItem-) |  |
| [visitPageEnd(ApsPage page)](#visitPageEnd-com.aspose.foundation.rendering.ApsPage-) |  |
| [visitPageStart(ApsPage page)](#visitPageStart-com.aspose.foundation.rendering.ApsPage-) |  |
| [visitPathEnd(ApsPath path)](#visitPathEnd-com.aspose.foundation.rendering.ApsPath-) |  |
| [visitPathFigureEnd(ApsPathFigure pathFigure)](#visitPathFigureEnd-com.aspose.foundation.rendering.ApsPathFigure-) |  |
| [visitPathFigureStart(ApsPathFigure pathFigure)](#visitPathFigureStart-com.aspose.foundation.rendering.ApsPathFigure-) |  |
| [visitPathStart(ApsPath path)](#visitPathStart-com.aspose.foundation.rendering.ApsPath-) |  |
| [visitPolyLineSegment(ApsPolyLineSegment segment)](#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options) {#ApsToFlowConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-}
```
public ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | com.aspose.foundation.DocumentInfo |  |
| options | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |

### dispose() {#dispose--}
```
public void dispose()
```




### endVisitGroup(ApsGroup arg0) {#endVisitGroup-com.aspose.foundation.rendering.ApsGroup-}
```
public void endVisitGroup(ApsGroup arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsGroup |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### render(ApsNode node) {#render-com.aspose.foundation.rendering.ApsNode-}
```
public void render(ApsNode node)
```


Renders a layout node and all its contents into a Excel document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | com.aspose.foundation.rendering.ApsNode | The aps node. |

### saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream) {#saveDocument-com.aspose.pdf.flow.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-}
```
public void saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | com.aspose.pdf.flow.OfficeConverterOptions |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### visitBezierSegment(ApsBezierSegment segment) {#visitBezierSegment-com.aspose.foundation.rendering.ApsBezierSegment-}
```
public void visitBezierSegment(ApsBezierSegment segment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsBezierSegment |  |

### visitBookmark(ApsBookmark arg0) {#visitBookmark-com.aspose.foundation.rendering.ApsBookmark-}
```
public void visitBookmark(ApsBookmark arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsBookmark |  |

### visitCanvasEnd(ApsCanvas arg0) {#visitCanvasEnd-com.aspose.foundation.rendering.ApsCanvas-}
```
public void visitCanvasEnd(ApsCanvas arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCanvas |  |

### visitCanvasStart(ApsCanvas arg0) {#visitCanvasStart-com.aspose.foundation.rendering.ApsCanvas-}
```
public void visitCanvasStart(ApsCanvas arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCanvas |  |

### visitFormComboBox(ApsComboBox arg0) {#visitFormComboBox-com.aspose.foundation.rendering.ApsComboBox-}
```
public void visitFormComboBox(ApsComboBox arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsComboBox |  |

### visitFormFieldButton(ApsButton arg0) {#visitFormFieldButton-com.aspose.foundation.rendering.ApsButton-}
```
public void visitFormFieldButton(ApsButton arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsButton |  |

### visitFormFieldCheckbox(ApsCheckBox arg0) {#visitFormFieldCheckbox-com.aspose.foundation.rendering.ApsCheckBox-}
```
public void visitFormFieldCheckbox(ApsCheckBox arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCheckBox |  |

### visitFormFieldRadioButton(ApsRadioButton arg0) {#visitFormFieldRadioButton-com.aspose.foundation.rendering.ApsRadioButton-}
```
public void visitFormFieldRadioButton(ApsRadioButton arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsRadioButton |  |

### visitFormFieldText(ApsTextField arg0) {#visitFormFieldText-com.aspose.foundation.rendering.ApsTextField-}
```
public void visitFormFieldText(ApsTextField arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsTextField |  |

### visitGlyphs(ApsGlyphs glyphs) {#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-}
```
public void visitGlyphs(ApsGlyphs glyphs)
```


Visits the glyphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| glyphs | com.aspose.foundation.rendering.ApsGlyphs | Internal instance |

### visitGroup(ApsGroup arg0) {#visitGroup-com.aspose.foundation.rendering.ApsGroup-}
```
public boolean visitGroup(ApsGroup arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsGroup |  |

**Returns:**
boolean
### visitImage(ApsImage image) {#visitImage-com.aspose.foundation.rendering.ApsImage-}
```
public void visitImage(ApsImage image)
```


Visits the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.foundation.rendering.ApsImage | The image. |

### visitOutlineItem(ApsOutlineItem arg0) {#visitOutlineItem-com.aspose.foundation.rendering.ApsOutlineItem-}
```
public void visitOutlineItem(ApsOutlineItem arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsOutlineItem |  |

### visitPageEnd(ApsPage page) {#visitPageEnd-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageEnd(ApsPage page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

### visitPageStart(ApsPage page) {#visitPageStart-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageStart(ApsPage page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

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

### visitPathStart(ApsPath path) {#visitPathStart-com.aspose.foundation.rendering.ApsPath-}
```
public void visitPathStart(ApsPath path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | com.aspose.foundation.rendering.ApsPath |  |

### visitPolyLineSegment(ApsPolyLineSegment segment) {#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-}
```
public void visitPolyLineSegment(ApsPolyLineSegment segment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsPolyLineSegment |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

