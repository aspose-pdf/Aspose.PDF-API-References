---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.AnnotationSelector. Этот класс используется для выбора аннотаций с использованием идеи шаблона Visitor
type: docs
weight: 1450
url: /ru/net/aspose.pdf.annotations/annotationselector/
---
## Класс AnnotationSelector

Этот класс используется для выбора аннотаций с использованием идеи шаблона Visitor.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | Инициализирует новый экземпляр класса AnnotationSelector. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | Инициализирует новый объект `AnnotationSelector`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | Список выбранных объектов. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | Выбирает *bleedMark*, если `AnnotationSelector` был инициализирован объектом [`BleedMarkAnnotation`](../bleedmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | Выбирает аннотацию курсора, если AnnotationSelector был инициализирован объектом CaretAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | Выбирает аннотацию круга, если AnnotationSelector был инициализирован объектом CircleAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | Выбирает аннотацию ColorBar, если AnnotationSelector был инициализирован объектом ColorBar. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | Выбирает аннотацию вложения, если AnnotationSelector был инициализирован объектом FileAttachmentAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | Выбирает аннотацию свободного текста, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | Выбирает аннотацию выделения, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | Выбирает аннотацию чернил, если AnnotationSelector был инициализирован объектом InkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | Выбирает аннотацию линии, если AnnotationSelector был инициализирован объектом LineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | Выбирает аннотацию ссылки, если AnnotationSelector был инициализирован объектом LinkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | Выбирает аннотацию фильма, если AnnotationSelector был инициализирован объектом MovieAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | Выбирает *pageInformation*, если `AnnotationSelector` был инициализирован объектом [`PageInformationAnnotation`](../pageinformationannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | Выбирает аннотацию PDF3D, если AnnotationSelector был инициализирован объектом PDF3DAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | Выбирает аннотацию многоугольника, если AnnotationSelector был инициализирован объектом PolygonAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | Выбирает аннотацию полилинии, если AnnotationSelector был инициализирован объектом PolylineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | Выбирает всплывающую аннотацию, если AnnotationSelector был инициализирован объектом PopupAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | Выбирает аннотацию редактирования, если AnnotationSelector был инициализирован объектом RedactAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | Выбирает *registrationMark*, если `AnnotationSelector` был инициализирован объектом [`RegistrationMarkAnnotation`](../registrationmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | Выбирает аннотацию фильма, если AnnotationSelector был инициализирован объектом аннотации RichMedia. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | Выбирает экранную аннотацию, если AnnotationSelector был инициализирован объектом ScreenAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | Выбирает квадратную аннотацию, если AnnotationSelector был инициализирован объектом SquareAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | Выбирает аннотацию волнистой линии, если AnnotationSelector был инициализирован объектом SquigglyAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | Выбирает аннотацию штампа, если AnnotationSelector был инициализирован объектом StampAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | Выбирает аннотацию зачеркивания, если AnnotationSelector был инициализирован объектом StrikeOutAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | Выбирает текстовую аннотацию, если AnnotationSelector был инициализирован объектом TextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | Выбирает *trimMark*, если `AnnotationSelector` был инициализирован объектом [`TrimMarkAnnotation`](../trimmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | Выбирает аннотацию подчеркивания, если AnnotationSelector был инициализирован объектом UnderlineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | Выбирает аннотацию водяного знака, если AnnotationSelector был инициализирован объектом WatermarkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | Выбирает виджет аннотации, если AnnotationSelector был инициализирован объектом WidgetAnnotation. |

### См. также

* интерфейс [IAnnotationVisitor](../iannotationvisitor/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)