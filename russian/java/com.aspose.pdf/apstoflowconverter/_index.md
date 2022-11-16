---
title: ApsToFlowConverter
second_title: Aspose.PDF для справки по Java API
description: Преобразование APS в поток
type: docs
weight: 27
url: /ru/java/com.aspose.pdf/apstoflowconverter/
---
**Наследование:**
java.lang.Object, com.aspose.foundation.rendering.ApsDocumentVisitor
```
public class ApsToFlowConverter extends ApsDocumentVisitor
```

 Преобразование APS в поток\* !!! Не портировать с C\# как можно раньше .Net версии!!!!
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ApsToFlowConverter(DocumentInfo info, ExcelSaveOptions options)](#ApsToFlowConverter-com.aspose.foundation.DocumentInfo-com.aspose.pdf.ExcelSaveOptions-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) |  |
| [endVisitGroup(ApsGroup arg0)](#endVisitGroup-com.aspose.foundation.rendering.ApsGroup-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [render(ApsNode node)](#render-com.aspose.foundation.rendering.ApsNode-) | Преобразует узел макета и все его содержимое в документ Excel. |
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
| [visitGlyphs(ApsGlyphs glyphs)](#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-) | Посещает глифы. |
| [visitGroup(ApsGroup arg0)](#visitGroup-com.aspose.foundation.rendering.ApsGroup-) |  |
| [visitImage(ApsImage image)](#visitImage-com.aspose.foundation.rendering.ApsImage-) | Посещает изображение. |
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


**Параметры:**

| Параметр | Тип | Описание |
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




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsGroup |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
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


Преобразует узел макета и все его содержимое в документ Excel.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | com.aspose.foundation.rendering.ApsNode | Узел апс. |

### saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream) {#saveDocument-com.aspose.pdf.flow.OfficeConverterOptions-com.aspose.ms.System.IO.Stream-}
```
public void saveDocument(OfficeConverterOptions options, System.IO.Stream outputStream)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | com.aspose.pdf.flow.OfficeConverterOptions |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visitBezierSegment(ApsBezierSegment segment) {#visitBezierSegment-com.aspose.foundation.rendering.ApsBezierSegment-}
```
public void visitBezierSegment(ApsBezierSegment segment)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| segment | com.aspose.foundation.rendering.ApsBezierSegment |  |

### visitBookmark(ApsBookmark arg0) {#visitBookmark-com.aspose.foundation.rendering.ApsBookmark-}
```
public void visitBookmark(ApsBookmark arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsBookmark |  |

### visitCanvasEnd(ApsCanvas arg0) {#visitCanvasEnd-com.aspose.foundation.rendering.ApsCanvas-}
```
public void visitCanvasEnd(ApsCanvas arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCanvas |  |

### visitCanvasStart(ApsCanvas arg0) {#visitCanvasStart-com.aspose.foundation.rendering.ApsCanvas-}
```
public void visitCanvasStart(ApsCanvas arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCanvas |  |

### visitFormComboBox(ApsComboBox arg0) {#visitFormComboBox-com.aspose.foundation.rendering.ApsComboBox-}
```
public void visitFormComboBox(ApsComboBox arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsComboBox |  |

### visitFormFieldButton(ApsButton arg0) {#visitFormFieldButton-com.aspose.foundation.rendering.ApsButton-}
```
public void visitFormFieldButton(ApsButton arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsButton |  |

### visitFormFieldCheckbox(ApsCheckBox arg0) {#visitFormFieldCheckbox-com.aspose.foundation.rendering.ApsCheckBox-}
```
public void visitFormFieldCheckbox(ApsCheckBox arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsCheckBox |  |

### visitFormFieldRadioButton(ApsRadioButton arg0) {#visitFormFieldRadioButton-com.aspose.foundation.rendering.ApsRadioButton-}
```
public void visitFormFieldRadioButton(ApsRadioButton arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsRadioButton |  |

### visitFormFieldText(ApsTextField arg0) {#visitFormFieldText-com.aspose.foundation.rendering.ApsTextField-}
```
public void visitFormFieldText(ApsTextField arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsTextField |  |

### visitGlyphs(ApsGlyphs glyphs) {#visitGlyphs-com.aspose.foundation.rendering.ApsGlyphs-}
```
public void visitGlyphs(ApsGlyphs glyphs)
```


Посещает глифы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| glyphs | com.aspose.foundation.rendering.ApsGlyphs | Внутренний экземпляр |

### visitGroup(ApsGroup arg0) {#visitGroup-com.aspose.foundation.rendering.ApsGroup-}
```
public boolean visitGroup(ApsGroup arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsGroup |  |

**Возвращает:**
логический
### visitImage(ApsImage image) {#visitImage-com.aspose.foundation.rendering.ApsImage-}
```
public void visitImage(ApsImage image)
```


Посещает изображение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | com.aspose.foundation.rendering.ApsImage | Изображение. |

### visitOutlineItem(ApsOutlineItem arg0) {#visitOutlineItem-com.aspose.foundation.rendering.ApsOutlineItem-}
```
public void visitOutlineItem(ApsOutlineItem arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | com.aspose.foundation.rendering.ApsOutlineItem |  |

### visitPageEnd(ApsPage page) {#visitPageEnd-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageEnd(ApsPage page)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

### visitPageStart(ApsPage page) {#visitPageStart-com.aspose.foundation.rendering.ApsPage-}
```
public void visitPageStart(ApsPage page)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | com.aspose.foundation.rendering.ApsPage |  |

### visitPathEnd(ApsPath path) {#visitPathEnd-com.aspose.foundation.rendering.ApsPath-}
```
public void visitPathEnd(ApsPath path)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | com.aspose.foundation.rendering.ApsPath |  |

### visitPathFigureEnd(ApsPathFigure pathFigure) {#visitPathFigureEnd-com.aspose.foundation.rendering.ApsPathFigure-}
```
public void visitPathFigureEnd(ApsPathFigure pathFigure)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pathFigure | com.aspose.foundation.rendering.ApsPathFigure |  |

### visitPathFigureStart(ApsPathFigure pathFigure) {#visitPathFigureStart-com.aspose.foundation.rendering.ApsPathFigure-}
```
public void visitPathFigureStart(ApsPathFigure pathFigure)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pathFigure | com.aspose.foundation.rendering.ApsPathFigure |  |

### visitPathStart(ApsPath path) {#visitPathStart-com.aspose.foundation.rendering.ApsPath-}
```
public void visitPathStart(ApsPath path)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | com.aspose.foundation.rendering.ApsPath |  |

### visitPolyLineSegment(ApsPolyLineSegment segment) {#visitPolyLineSegment-com.aspose.foundation.rendering.ApsPolyLineSegment-}
```
public void visitPolyLineSegment(ApsPolyLineSegment segment)
```




**Параметры:**

| Параметр | Тип | Описание |
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




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
