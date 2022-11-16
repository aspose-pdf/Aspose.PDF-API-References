---
title: AnnotationSelector
second_title: Aspose.PDF для справки по Java API
description: Этот класс используется для выбора аннотаций с использованием идеи шаблона посетителя.
type: docs
weight: 19
url: /ru/java/com.aspose.pdf/annotationselector/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.pdf.IAnnotationVisitor](../../com.aspose.pdf/iannotationvisitor)
```
public final class AnnotationSelector implements IAnnotationVisitor
```

Этот класс используется для выбора аннотаций с использованием идеи шаблона посетителя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AnnotationSelector()](#AnnotationSelector--) | Инициализирует новый экземпляр класса AnnotationSelector. |
| [AnnotationSelector(Annotation annotation)](#AnnotationSelector-com.aspose.pdf.Annotation-) | Инициализирует новый объект AnnotationSelector. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSelected()](#getSelected--) | Список выбранных объектов. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(CaretAnnotation caret)](#visit-com.aspose.pdf.CaretAnnotation-) | Выберите аннотацию вставки, если AnnotationSelector был инициализирован объектом CaretAnnotation. |
| [visit(CircleAnnotation circle)](#visit-com.aspose.pdf.CircleAnnotation-) | Выберите круговую аннотацию, если AnnotationSelector был инициализирован объектом CircleAnnotation. |
| [visit(FileAttachmentAnnotation attachment)](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Выберите аннотацию вложения, если AnnotationSelector был инициализирован объектом FileAttachmentAnnotation. |
| [visit(FreeTextAnnotation freetext)](#visit-com.aspose.pdf.FreeTextAnnotation-) | Выберите аннотацию произвольного текста, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [visit(HighlightAnnotation highlight)](#visit-com.aspose.pdf.HighlightAnnotation-) | Выберите аннотацию вложения, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [visit(InkAnnotation ink)](#visit-com.aspose.pdf.InkAnnotation-) | Выберите рукописную аннотацию, если AnnotationSelector был инициализирован объектом InkAnnotation. |
| [visit(LineAnnotation line)](#visit-com.aspose.pdf.LineAnnotation-) | Выбрать линейную аннотацию, если AnnotationSelector был инициализирован объектом LineAnnotation. |
| [visit(LinkAnnotation link)](#visit-com.aspose.pdf.LinkAnnotation-) | Выберите аннотацию ссылки, если AnnotationSelector был инициализирован с помощью объекта LinkAnnotation. |
| [visit(MovieAnnotation movie)](#visit-com.aspose.pdf.MovieAnnotation-) | Выберите аннотацию фильма, если AnnotationSelector был инициализирован с помощью объекта MovieAnnotation. |
| [visit(PDF3DAnnotation pdf3D)](#visit-com.aspose.pdf.PDF3DAnnotation-) | Выберите аннотацию PDF3D, если AnnotationSelector был инициализирован объектом PDF3DAnnotation. |
| [visit(PolygonAnnotation polygon)](#visit-com.aspose.pdf.PolygonAnnotation-) | Выберите полигональную аннотацию, если AnnotationSelector был инициализирован объектом PolygonAnnotation. |
| [visit(PolylineAnnotation polyline)](#visit-com.aspose.pdf.PolylineAnnotation-) | Выберите полилинейную аннотацию, если AnnotationSelector был инициализирован объектом PolylineAnnotation. |
| [visit(PopupAnnotation popup)](#visit-com.aspose.pdf.PopupAnnotation-) | Выберите всплывающую аннотацию, если AnnotationSelector был инициализирован объектом PopupAnnotation. |
| [visit(RedactionAnnotation redact)](#visit-com.aspose.pdf.RedactionAnnotation-) | Выберите редактируемую аннотацию, если AnnotationSelector был инициализирован объектом RedactAnnotation. |
| [visit(RichMediaAnnotation richMedia)](#visit-com.aspose.pdf.RichMediaAnnotation-) | Выберите аннотацию фильма, если AnnotationSelector был инициализирован с помощью объекта аннотации RichMedia. |
| [visit(ScreenAnnotation screen)](#visit-com.aspose.pdf.ScreenAnnotation-) | Выберите аннотацию экрана, если AnnotationSelector был инициализирован объектом ScreenAnnotation. |
| [visit(SquareAnnotation square)](#visit-com.aspose.pdf.SquareAnnotation-) | Выберите квадратную аннотацию, если AnnotationSelector был инициализирован объектом SquareAnnotation. |
| [visit(SquigglyAnnotation squiggly)](#visit-com.aspose.pdf.SquigglyAnnotation-) | Выберите волнистую аннотацию, если AnnotationSelector был инициализирован с помощью объекта SquigglyAnnotation. |
| [visit(StampAnnotation stamp)](#visit-com.aspose.pdf.StampAnnotation-) | Выберите аннотацию штампа, если AnnotationSelector был инициализирован с помощью объекта StampAnnotation. |
| [visit(StrikeOutAnnotation strikeOut)](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Выберите аннотацию strikeOut, если AnnotationSelector был инициализирован с помощью объекта StrikeOutAnnotation. |
| [visit(TextAnnotation text)](#visit-com.aspose.pdf.TextAnnotation-) | Выберите текстовую аннотацию, если AnnotationSelector был инициализирован объектом TextAnnotation. |
| [visit(UnderlineAnnotation underline)](#visit-com.aspose.pdf.UnderlineAnnotation-) | Выберите аннотацию подчеркивания, если AnnotationSelector был инициализирован объектом UnderlineAnnotation. |
| [visit(WatermarkAnnotation watermark)](#visit-com.aspose.pdf.WatermarkAnnotation-) | Выберите аннотацию водяного знака, если AnnotationSelector был инициализирован объектом WatermarkAnnotation. |
| [visit(WidgetAnnotation widget)](#visit-com.aspose.pdf.WidgetAnnotation-) | Выберите аннотацию виджета, если AnnotationSelector был инициализирован объектом WidgetAnnotation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnnotationSelector() {#AnnotationSelector--}
```
public AnnotationSelector()
```


Инициализирует новый экземпляр класса AnnotationSelector.

### AnnotationSelector(Annotation annotation) {#AnnotationSelector-com.aspose.pdf.Annotation-}
```
public AnnotationSelector(Annotation annotation)
```


Инициализирует новый объект AnnotationSelector.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация для выбора. Этот объект описывает только некоторые характеристики, которые должны быть у найденных аннотаций, например, тип аннотации. |

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
### getSelected() {#getSelected--}
```
public List<Annotation> getSelected()
```


Список выбранных объектов.

**Возвращает:**
java.util.List<com.aspose.pdf.Annotation> — Список экземпляров аннотаций
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




### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visit(CaretAnnotation caret) {#visit-com.aspose.pdf.CaretAnnotation-}
```
public void visit(CaretAnnotation caret)
```


Выберите аннотацию вставки, если AnnotationSelector был инициализирован объектом CaretAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| caret | [CaretAnnotation](../../com.aspose.pdf/caretannotation) | Объект CaretAnnotation для выбора. |

### visit(CircleAnnotation circle) {#visit-com.aspose.pdf.CircleAnnotation-}
```
public void visit(CircleAnnotation circle)
```


Выберите круговую аннотацию, если AnnotationSelector был инициализирован объектом CircleAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| circle | [CircleAnnotation](../../com.aspose.pdf/circleannotation) | Объект CircleAnnotation для выбора. |

### visit(FileAttachmentAnnotation attachment) {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
```
public void visit(FileAttachmentAnnotation attachment)
```


Выберите аннотацию вложения, если AnnotationSelector был инициализирован объектом FileAttachmentAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| attachment | [FileAttachmentAnnotation](../../com.aspose.pdf/fileattachmentannotation) | Объект FileAttachmentAnnotation для выбора. |

### visit(FreeTextAnnotation freetext) {#visit-com.aspose.pdf.FreeTextAnnotation-}
```
public void visit(FreeTextAnnotation freetext)
```


Выберите аннотацию произвольного текста, если AnnotationSelector был инициализирован объектом FreeTextAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| freetext | [FreeTextAnnotation](../../com.aspose.pdf/freetextannotation) | Объект FreeTextAnnotation для выбора. |

### visit(HighlightAnnotation highlight) {#visit-com.aspose.pdf.HighlightAnnotation-}
```
public void visit(HighlightAnnotation highlight)
```


Выберите аннотацию вложения, если AnnotationSelector был инициализирован объектом FreeTextAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| highlight | [HighlightAnnotation](../../com.aspose.pdf/highlightannotation) | Объект HighlightAnnotation для выбора. |

### visit(InkAnnotation ink) {#visit-com.aspose.pdf.InkAnnotation-}
```
public void visit(InkAnnotation ink)
```


Выберите рукописную аннотацию, если AnnotationSelector был инициализирован объектом InkAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ink | [InkAnnotation](../../com.aspose.pdf/inkannotation) | Объект InkAnnotation для выбора. |

### visit(LineAnnotation line) {#visit-com.aspose.pdf.LineAnnotation-}
```
public void visit(LineAnnotation line)
```


Выбрать линейную аннотацию, если AnnotationSelector был инициализирован объектом LineAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | [LineAnnotation](../../com.aspose.pdf/lineannotation) | Объект LineAnnotation для выбора. |

### visit(LinkAnnotation link) {#visit-com.aspose.pdf.LinkAnnotation-}
```
public void visit(LinkAnnotation link)
```


Выберите аннотацию ссылки, если AnnotationSelector был инициализирован с помощью объекта LinkAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| link | [LinkAnnotation](../../com.aspose.pdf/linkannotation) | Объект LinkAnnotation для выбора. |

### visit(MovieAnnotation movie) {#visit-com.aspose.pdf.MovieAnnotation-}
```
public void visit(MovieAnnotation movie)
```


Выберите аннотацию фильма, если AnnotationSelector был инициализирован с помощью объекта MovieAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| movie | [MovieAnnotation](../../com.aspose.pdf/movieannotation) | Объект MovieAnnotation для выбора. |

### visit(PDF3DAnnotation pdf3D) {#visit-com.aspose.pdf.PDF3DAnnotation-}
```
public void visit(PDF3DAnnotation pdf3D)
```


Выберите аннотацию PDF3D, если AnnotationSelector был инициализирован объектом PDF3DAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf3D | [PDF3DAnnotation](../../com.aspose.pdf/pdf3dannotation) | Объект PDF3DAnnotation для выбора. |

### visit(PolygonAnnotation polygon) {#visit-com.aspose.pdf.PolygonAnnotation-}
```
public void visit(PolygonAnnotation polygon)
```


Выберите полигональную аннотацию, если AnnotationSelector был инициализирован объектом PolygonAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| polygon | [PolygonAnnotation](../../com.aspose.pdf/polygonannotation) | Объект PolygonAnnotation для выбора. |

### visit(PolylineAnnotation polyline) {#visit-com.aspose.pdf.PolylineAnnotation-}
```
public void visit(PolylineAnnotation polyline)
```


Выберите полилинейную аннотацию, если AnnotationSelector был инициализирован объектом PolylineAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| polyline | [PolylineAnnotation](../../com.aspose.pdf/polylineannotation) | Объект PolylineAnnotation для выбора. |

### visit(PopupAnnotation popup) {#visit-com.aspose.pdf.PopupAnnotation-}
```
public void visit(PopupAnnotation popup)
```


Выберите всплывающую аннотацию, если AnnotationSelector был инициализирован объектом PopupAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| popup | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | Объект PopupAnnotation для выбора. |

### visit(RedactionAnnotation redact) {#visit-com.aspose.pdf.RedactionAnnotation-}
```
public void visit(RedactionAnnotation redact)
```


Выберите редактируемую аннотацию, если AnnotationSelector был инициализирован объектом RedactAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| redact | [RedactionAnnotation](../../com.aspose.pdf/redactionannotation) | Объект RedactAnnotation для выбора. |

### visit(RichMediaAnnotation richMedia) {#visit-com.aspose.pdf.RichMediaAnnotation-}
```
public void visit(RichMediaAnnotation richMedia)
```


Выберите аннотацию фильма, если AnnotationSelector был инициализирован с помощью объекта аннотации RichMedia.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| richMedia | [RichMediaAnnotation](../../com.aspose.pdf/richmediaannotation) | Аннотация RichMedia. |

### visit(ScreenAnnotation screen) {#visit-com.aspose.pdf.ScreenAnnotation-}
```
public void visit(ScreenAnnotation screen)
```


Выберите аннотацию экрана, если AnnotationSelector был инициализирован объектом ScreenAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | Объект ScreenAnnotation для выбора. |

### visit(SquareAnnotation square) {#visit-com.aspose.pdf.SquareAnnotation-}
```
public void visit(SquareAnnotation square)
```


Выберите квадратную аннотацию, если AnnotationSelector был инициализирован объектом SquareAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| square | [SquareAnnotation](../../com.aspose.pdf/squareannotation) | Объект SquareAnnotation для выбора. |

### visit(SquigglyAnnotation squiggly) {#visit-com.aspose.pdf.SquigglyAnnotation-}
```
public void visit(SquigglyAnnotation squiggly)
```


Выберите волнистую аннотацию, если AnnotationSelector был инициализирован с помощью объекта SquigglyAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| squiggly | [SquigglyAnnotation](../../com.aspose.pdf/squigglyannotation) | Объект SquigglyAnnotation для выбора. |

### visit(StampAnnotation stamp) {#visit-com.aspose.pdf.StampAnnotation-}
```
public void visit(StampAnnotation stamp)
```


Выберите аннотацию штампа, если AnnotationSelector был инициализирован с помощью объекта StampAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stamp | [StampAnnotation](../../com.aspose.pdf/stampannotation) | Объект StampAnnotation для выбора. |

### visit(StrikeOutAnnotation strikeOut) {#visit-com.aspose.pdf.StrikeOutAnnotation-}
```
public void visit(StrikeOutAnnotation strikeOut)
```


Выберите аннотацию strikeOut, если AnnotationSelector был инициализирован с помощью объекта StrikeOutAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| strikeOut | [StrikeOutAnnotation](../../com.aspose.pdf/strikeoutannotation) | Объект StrikeOutAnnotation для выбора. |

### visit(TextAnnotation text) {#visit-com.aspose.pdf.TextAnnotation-}
```
public void visit(TextAnnotation text)
```


Выберите текстовую аннотацию, если AnnotationSelector был инициализирован объектом TextAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [TextAnnotation](../../com.aspose.pdf/textannotation) | Объект TextAnnotation для выбора. |

### visit(UnderlineAnnotation underline) {#visit-com.aspose.pdf.UnderlineAnnotation-}
```
public void visit(UnderlineAnnotation underline)
```


Выберите аннотацию подчеркивания, если AnnotationSelector был инициализирован объектом UnderlineAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| underline | [UnderlineAnnotation](../../com.aspose.pdf/underlineannotation) | Объект UnderlineAnnotation для выбора. |

### visit(WatermarkAnnotation watermark) {#visit-com.aspose.pdf.WatermarkAnnotation-}
```
public void visit(WatermarkAnnotation watermark)
```


Выберите аннотацию водяного знака, если AnnotationSelector был инициализирован объектом WatermarkAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| watermark | [WatermarkAnnotation](../../com.aspose.pdf/watermarkannotation) | Водяной знакАннотация для выбора. |

### visit(WidgetAnnotation widget) {#visit-com.aspose.pdf.WidgetAnnotation-}
```
public void visit(WidgetAnnotation widget)
```


Выберите аннотацию виджета, если AnnotationSelector был инициализирован объектом WidgetAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| widget | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Объект WidgetAnnotation для выбора. |

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
