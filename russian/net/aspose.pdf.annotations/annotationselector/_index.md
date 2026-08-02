---
title: "Класс AnnotationSelector"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.AnnotationSelector. Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor."
type: docs
weight: 1540
url: /ru/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class

Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor.

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
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | Выбирает аннотацию caret, если AnnotationSelector был инициализирован объектом CaretAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | Выбирает аннотацию circle, если AnnotationSelector был инициализирован объектом CircleAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | Выбирает аннотацию ColorBar, если AnnotationSelector был инициализирован объектом ColorBar. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | Выбирает аннотацию attachment, если AnnotationSelector был инициализирован объектом FileAttachmentAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | Выбирает аннотацию freetext, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | Выбирает аннотацию attachment, если AnnotationSelector был инициализирован объектом FreeTextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | Выбирает аннотацию ink, если AnnotationSelector был инициализирован объектом InkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | Выбирает аннотацию line, если AnnotationSelector был инициализирован объектом LineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | Выбирает аннотацию link, если AnnotationSelector был инициализирован объектом LinkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | Выберите аннотацию фильма, если AnnotationSelector был инициализирован объектом MovieAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | Выбирает *pageInformation*, если `AnnotationSelector` был инициализирован объектом [`PageInformationAnnotation`](../pageinformationannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | Выберите аннотацию PDF3D, если AnnotationSelector был инициализирован объектом PDF3DAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | Выберите полигональную аннотацию, если AnnotationSelector был инициализирован объектом PolygonAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | Выберите полилинейную аннотацию, если AnnotationSelector был инициализирован объектом PolylineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | Выберите всплывающую аннотацию, если AnnotationSelector был инициализирован объектом PopupAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | Выберите аннотацию редактирования, если AnnotationSelector был инициализирован объектом RedactAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | Выбирает *registrationMark*, если `AnnotationSelector` был инициализирован объектом [`RegistrationMarkAnnotation`](../registrationmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | Выберите аннотацию фильма, если AnnotationSelector был инициализирован объектом RichMedia annotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | Выберите аннотацию экрана, если AnnotationSelector был инициализирован объектом ScreenAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | Выберите квадратную аннотацию, если AnnotationSelector был инициализирован объектом SquareAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | Выберите волнообразную аннотацию, если AnnotationSelector был инициализирован объектом SquigglyAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | Выберите штампованную аннотацию, если AnnotationSelector был инициализирован объектом StampAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | Выберите аннотацию зачеркивания, если AnnotationSelector был инициализирован объектом StrikeOutAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | Выберите текстовую аннотацию, если AnnotationSelector был инициализирован объектом TextAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | Выбирает *trimMark*, если `AnnotationSelector` был инициализирован объектом [`TrimMarkAnnotation`](../trimmarkannotation/). |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | Выберите аннотацию подчеркивания, если AnnotationSelector был инициализирован объектом UnderlineAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | Выберите аннотацию водяного знака, если AnnotationSelector был инициализирован объектом WatermarkAnnotation. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | Выберите виджет-аннотацию, если AnnotationSelector был инициализирован объектом WidgetAnnotation. |

### См. также

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


