---
title: IAnnotationVisitor
second_title: Aspose.PDF для справки по Java API
description: Определяет посетителя для посещения различных аннотаций документа.
type: docs
weight: 430
url: /ru/java/com.aspose.pdf/iannotationvisitor/
---
```
public interface IAnnotationVisitor
```

Определяет посетителя для посещения различных аннотаций документа.
## Методы

| Метод | Описание |
| --- | --- |
| [visit(CaretAnnotation caret)](#visit-com.aspose.pdf.CaretAnnotation-) | Посетите/выберите курсорную аннотацию. |
| [visit(CircleAnnotation circle)](#visit-com.aspose.pdf.CircleAnnotation-) | Посетите/выберите круговую аннотацию. |
| [visit(FileAttachmentAnnotation attachment)](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Посетите/выберите аннотацию вложения. |
| [visit(FreeTextAnnotation freetext)](#visit-com.aspose.pdf.FreeTextAnnotation-) | Посетите/выберите аннотацию произвольного текста. |
| [visit(HighlightAnnotation highlight)](#visit-com.aspose.pdf.HighlightAnnotation-) | Посетите/выберите выделенную аннотацию. |
| [visit(InkAnnotation ink)](#visit-com.aspose.pdf.InkAnnotation-) | Посетите/выберите рукописную аннотацию. |
| [visit(LineAnnotation line)](#visit-com.aspose.pdf.LineAnnotation-) | Посетите/выберите аннотацию строки. |
| [visit(LinkAnnotation link)](#visit-com.aspose.pdf.LinkAnnotation-) | Посетите/выберите аннотацию ссылки. |
| [visit(MovieAnnotation movie)](#visit-com.aspose.pdf.MovieAnnotation-) | Посетите/выберите аннотацию к фильму. |
| [visit(PolygonAnnotation polygon)](#visit-com.aspose.pdf.PolygonAnnotation-) | Посетите/выберите аннотацию полигона. |
| [visit(PolylineAnnotation polyline)](#visit-com.aspose.pdf.PolylineAnnotation-) | Посетите/выберите полилинейную аннотацию. |
| [visit(PopupAnnotation popup)](#visit-com.aspose.pdf.PopupAnnotation-) | Посетите/выберите всплывающую аннотацию. |
| [visit(ScreenAnnotation screen)](#visit-com.aspose.pdf.ScreenAnnotation-) | Посетите/выберите аннотацию экрана. |
| [visit(SquareAnnotation square)](#visit-com.aspose.pdf.SquareAnnotation-) | Посетите/выберите квадратную аннотацию. |
| [visit(SquigglyAnnotation squiggly)](#visit-com.aspose.pdf.SquigglyAnnotation-) | Посетите/выберите волнистую аннотацию. |
| [visit(StampAnnotation stamp)](#visit-com.aspose.pdf.StampAnnotation-) | Посетите/выберите аннотацию штампа. |
| [visit(StrikeOutAnnotation strikeOut)](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Посетите/выберите аннотацию strikeOut. |
| [visit(TextAnnotation text)](#visit-com.aspose.pdf.TextAnnotation-) | Посетите/выберите текстовую аннотацию. |
| [visit(UnderlineAnnotation underline)](#visit-com.aspose.pdf.UnderlineAnnotation-) | Посетите/выберите подчеркнутую аннотацию. |
| [visit(WidgetAnnotation widget)](#visit-com.aspose.pdf.WidgetAnnotation-) | Посетите/выберите аннотацию виджета. |
### visit(CaretAnnotation caret) {#visit-com.aspose.pdf.CaretAnnotation-}
```
public abstract void visit(CaretAnnotation caret)
```


Посетите/выберите курсорную аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| caret | [CaretAnnotation](../../com.aspose.pdf/caretannotation) | Пример/шаблон объекта CaretAnnotation. |

### visit(CircleAnnotation circle) {#visit-com.aspose.pdf.CircleAnnotation-}
```
public abstract void visit(CircleAnnotation circle)
```


Посетите/выберите круговую аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| circle | [CircleAnnotation](../../com.aspose.pdf/circleannotation) | Пример/шаблон объекта CircleAnnotation. |

### visit(FileAttachmentAnnotation attachment) {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
```
public abstract void visit(FileAttachmentAnnotation attachment)
```


Посетите/выберите аннотацию вложения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| attachment | [FileAttachmentAnnotation](../../com.aspose.pdf/fileattachmentannotation) | Пример/шаблон объекта FileAttachmentAnnotation. |

### visit(FreeTextAnnotation freetext) {#visit-com.aspose.pdf.FreeTextAnnotation-}
```
public abstract void visit(FreeTextAnnotation freetext)
```


Посетите/выберите аннотацию произвольного текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| freetext | [FreeTextAnnotation](../../com.aspose.pdf/freetextannotation) | Пример/шаблон объекта FreeTextAnnotation. |

### visit(HighlightAnnotation highlight) {#visit-com.aspose.pdf.HighlightAnnotation-}
```
public abstract void visit(HighlightAnnotation highlight)
```


Посетите/выберите выделенную аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| highlight | [HighlightAnnotation](../../com.aspose.pdf/highlightannotation) | Пример/шаблон объекта HighlightAnnotation. |

### visit(InkAnnotation ink) {#visit-com.aspose.pdf.InkAnnotation-}
```
public abstract void visit(InkAnnotation ink)
```


Посетите/выберите рукописную аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ink | [InkAnnotation](../../com.aspose.pdf/inkannotation) | Пример/шаблон объекта InkAnnotation. |

### visit(LineAnnotation line) {#visit-com.aspose.pdf.LineAnnotation-}
```
public abstract void visit(LineAnnotation line)
```


Посетите/выберите аннотацию строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | [LineAnnotation](../../com.aspose.pdf/lineannotation) | Пример/шаблон объекта LineAnnotation. |

### visit(LinkAnnotation link) {#visit-com.aspose.pdf.LinkAnnotation-}
```
public abstract void visit(LinkAnnotation link)
```


Посетите/выберите аннотацию ссылки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| link | [LinkAnnotation](../../com.aspose.pdf/linkannotation) | Пример/шаблон объекта LinkAnnotation. |

### visit(MovieAnnotation movie) {#visit-com.aspose.pdf.MovieAnnotation-}
```
public abstract void visit(MovieAnnotation movie)
```


Посетите/выберите аннотацию к фильму.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| movie | [MovieAnnotation](../../com.aspose.pdf/movieannotation) | Пример/шаблон объекта MovieAnnotation. |

### visit(PolygonAnnotation polygon) {#visit-com.aspose.pdf.PolygonAnnotation-}
```
public abstract void visit(PolygonAnnotation polygon)
```


Посетите/выберите аннотацию полигона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| polygon | [PolygonAnnotation](../../com.aspose.pdf/polygonannotation) | Пример/шаблон объекта PolygonAnnotation. |

### visit(PolylineAnnotation polyline) {#visit-com.aspose.pdf.PolylineAnnotation-}
```
public abstract void visit(PolylineAnnotation polyline)
```


Посетите/выберите полилинейную аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| polyline | [PolylineAnnotation](../../com.aspose.pdf/polylineannotation) | Пример/шаблон объекта PolylineAnnotation. |

### visit(PopupAnnotation popup) {#visit-com.aspose.pdf.PopupAnnotation-}
```
public abstract void visit(PopupAnnotation popup)
```


Посетите/выберите всплывающую аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| popup | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | Пример/шаблон объекта PopupAnnotation. |

### visit(ScreenAnnotation screen) {#visit-com.aspose.pdf.ScreenAnnotation-}
```
public abstract void visit(ScreenAnnotation screen)
```


Посетите/выберите аннотацию экрана.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | Пример/шаблон объекта ScreenAnnotation. |

### visit(SquareAnnotation square) {#visit-com.aspose.pdf.SquareAnnotation-}
```
public abstract void visit(SquareAnnotation square)
```


Посетите/выберите квадратную аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| square | [SquareAnnotation](../../com.aspose.pdf/squareannotation) | Пример/шаблон объекта SquareAnnotation. |

### visit(SquigglyAnnotation squiggly) {#visit-com.aspose.pdf.SquigglyAnnotation-}
```
public abstract void visit(SquigglyAnnotation squiggly)
```


Посетите/выберите волнистую аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| squiggly | [SquigglyAnnotation](../../com.aspose.pdf/squigglyannotation) | Пример/шаблон объекта SquigglyAnnotation. |

### visit(StampAnnotation stamp) {#visit-com.aspose.pdf.StampAnnotation-}
```
public abstract void visit(StampAnnotation stamp)
```


Посетите/выберите аннотацию штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stamp | [StampAnnotation](../../com.aspose.pdf/stampannotation) | Пример/шаблон объекта StampAnnotation. |

### visit(StrikeOutAnnotation strikeOut) {#visit-com.aspose.pdf.StrikeOutAnnotation-}
```
public abstract void visit(StrikeOutAnnotation strikeOut)
```


Посетите/выберите аннотацию strikeOut.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| strikeOut | [StrikeOutAnnotation](../../com.aspose.pdf/strikeoutannotation) | Пример/шаблон объекта StrikeOutAnnotation. |

### visit(TextAnnotation text) {#visit-com.aspose.pdf.TextAnnotation-}
```
public abstract void visit(TextAnnotation text)
```


Посетите/выберите текстовую аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [TextAnnotation](../../com.aspose.pdf/textannotation) | Пример/шаблон объекта TextAnnotation. |

### visit(UnderlineAnnotation underline) {#visit-com.aspose.pdf.UnderlineAnnotation-}
```
public abstract void visit(UnderlineAnnotation underline)
```


Посетите/выберите подчеркнутую аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| underline | [UnderlineAnnotation](../../com.aspose.pdf/underlineannotation) | Пример/шаблон объекта UnderlineAnnotation. |

### visit(WidgetAnnotation widget) {#visit-com.aspose.pdf.WidgetAnnotation-}
```
public abstract void visit(WidgetAnnotation widget)
```


Посетите/выберите аннотацию виджета.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| widget | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Пример/шаблон объекта WidgetAnnotation. |
