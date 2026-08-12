---
title: "Aspose::Pdf::Annotations::AnnotationSelector class"
linktitle: "AnnotationSelector"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AnnotationSelector class. Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class


Этот класс используется для выбора аннотаций с помощью идеи шаблона Visitor.

```cpp
class AnnotationSelector : public Aspose::Pdf::Annotations::IAnnotationVisitor
```

## Методы

| Метод | Описание |
| --- | --- |
| [AnnotationSelector](./annotationselector/)() | Инициализирует новый экземпляр класса [AnnotationSelector](./). |
| [AnnotationSelector](./annotationselector/)(const System::SharedPtr\<Annotation\>\&) | Инициализирует новый объект [AnnotationSelector](./). |
| [get_Selected](./get_selected/)() const | Список выбранных объектов. |
| [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) override | Выберите аннотацию ссылки, если [AnnotationSelector](./) был инициализирован объектом [LinkAnnotation](../linkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) override | Выберите аннотацию вложения, если [AnnotationSelector](./) был инициализирован объектом [FileAttachmentAnnotation](../fileattachmentannotation/). |
| [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) override | Выберите текстовую аннотацию, если [AnnotationSelector](./) был инициализирован объектом [TextAnnotation](../textannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<RedactionAnnotation\>\&) | Выберите аннотацию редактирования, если [AnnotationSelector](./) был инициализирован объектом RedactAnnotation. |
| [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) override | Выберите аннотацию свободного текста, если [AnnotationSelector](./) был инициализирован объектом [FreeTextAnnotation](../freetextannotation/). |
| [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) override | Выберите аннотацию вложения, если [AnnotationSelector](./) был инициализирован объектом [FreeTextAnnotation](../freetextannotation/). |
| [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) override | Выберите аннотацию подчеркивания, если [AnnotationSelector](./) был инициализирован объектом [UnderlineAnnotation](../underlineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) override | Выберите аннотацию зачеркивания, если [AnnotationSelector](./) был инициализирован объектом [StrikeOutAnnotation](../strikeoutannotation/). |
| [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) override | Выберите аннотацию волнистой линии, если [AnnotationSelector](./) был инициализирован объектом [SquigglyAnnotation](../squigglyannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) override | Выберите всплывающую аннотацию, если [AnnotationSelector](./) был инициализирован объектом [PopupAnnotation](../popupannotation/). |
| [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) override | Выберите линейную аннотацию, если [AnnotationSelector](./) был инициализирован объектом [LineAnnotation](../lineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) override | Выберите круглую аннотацию, если [AnnotationSelector](./) был инициализирован объектом [CircleAnnotation](../circleannotation/). |
| [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) override | Выберите квадратную аннотацию, если [AnnotationSelector](./) был инициализирован объектом [SquareAnnotation](../squareannotation/). |
| [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) override | Выберите аннотацию чернил, если [AnnotationSelector](./) был инициализирован объектом [InkAnnotation](../inkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) override | Выберите аннотацию полилинии, если [AnnotationSelector](./) был инициализирован объектом [PolylineAnnotation](../polylineannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) override | Выберите аннотацию многоугольника, если [AnnotationSelector](./) был инициализирован объектом [PolygonAnnotation](../polygonannotation/). |
| [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) override | Выберите аннотацию каретки, если [AnnotationSelector](./) был инициализирован объектом [CaretAnnotation](../caretannotation/). |
| [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) override | Выберите аннотацию штампа, если [AnnotationSelector](./) был инициализирован объектом [StampAnnotation](../stampannotation/). |
| [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) override | Выберите аннотацию виджета, если [AnnotationSelector](./) был инициализирован объектом [WidgetAnnotation](../widgetannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<WatermarkAnnotation\>\&) | Выберите аннотацию водяного знака, если [AnnotationSelector](./) был инициализирован объектом [WatermarkAnnotation](../watermarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) override | Выберите аннотацию фильма, если [AnnotationSelector](./) был инициализирован объектом [MovieAnnotation](../movieannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<RichMediaAnnotation\>\&) | Выберите аннотацию фильма, если [AnnotationSelector](./) был инициализирован объектом аннотации RichMedia. |
| [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) override | Выберите аннотацию экрана, если [AnnotationSelector](./) был инициализирован объектом [ScreenAnnotation](../screenannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<PDF3DAnnotation\>\&) | Выберите аннотацию PDF3D, если [AnnotationSelector](./) был инициализирован объектом [PDF3DAnnotation](../pdf3dannotation/). |
| [Visit](./visit/)(const System::SharedPtr\<ColorBarAnnotation\>\&) | Выберите аннотацию ColorBar, если [AnnotationSelector](./) был инициализирован объектом ColorBar. |
| [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) override | Выбирает *trimMark*, если [AnnotationSelector](./) был инициализирован объектом [TrimMarkAnnotation](../trimmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) override | Выбирает *bleedMark*, если [AnnotationSelector](./) был инициализирован объектом [BleedMarkAnnotation](../bleedmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) override | Выбирает *registrationMark*, если [AnnotationSelector](./) был инициализирован объектом [RegistrationMarkAnnotation](../registrationmarkannotation/). |
| [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) override | Выбирает *pageInformation*, если [AnnotationSelector](./) был инициализирован объектом [PageInformationAnnotation](../pageinformationannotation/). |
## См. также

* Class [IAnnotationVisitor](../iannotationvisitor/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
