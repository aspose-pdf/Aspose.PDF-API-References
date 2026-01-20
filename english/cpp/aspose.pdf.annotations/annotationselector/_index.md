---
title: Aspose::Pdf::Annotations::AnnotationSelector class
linktitle: AnnotationSelector
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AnnotationSelector class. This class is used for selecting annotations using Visitor template idea in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class


This class is used for selecting annotations using Visitor template idea.

```cpp
class AnnotationSelector : public Aspose::Pdf::Annotations::IAnnotationVisitor
```

## Methods

| Method | Description |
| --- | --- |
| [AnnotationSelector](./annotationselector/)() | Initializes new instance of the [AnnotationSelector](./) class. |
| [AnnotationSelector](./annotationselector/)(System::SharedPtr\<Annotation\>) | Initializes new [AnnotationSelector](./) object. |
| [get_Selected](./get_selected/)() const | The list of selected objects. |
| [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) override | Select link annotation if [AnnotationSelector](./) was initialized with [LinkAnnotation](../linkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) override | Select attachment annotation if [AnnotationSelector](./) was initialized with [FileAttachmentAnnotation](../fileattachmentannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) override | Select text annotation if [AnnotationSelector](./) was initialized with [TextAnnotation](../textannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<RedactionAnnotation\>) | Select redact annotation if [AnnotationSelector](./) was initialized with RedactAnnotation object. |
| [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) override | Select freetext annotation if [AnnotationSelector](./) was initialized with [FreeTextAnnotation](../freetextannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) override | Select attachment annotation if [AnnotationSelector](./) was initialized with [FreeTextAnnotation](../freetextannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) override | Select underline annotation if [AnnotationSelector](./) was initialized with [UnderlineAnnotation](../underlineannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) override | Select strikeOut annotation if [AnnotationSelector](./) was initialized with [StrikeOutAnnotation](../strikeoutannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) override | Select squiggly annotation if [AnnotationSelector](./) was initialized with [SquigglyAnnotation](../squigglyannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) override | Select popup annotation if [AnnotationSelector](./) was initialized with [PopupAnnotation](../popupannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) override | Select line annotation if [AnnotationSelector](./) was initialized with [LineAnnotation](../lineannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) override | Select circle annotation if [AnnotationSelector](./) was initialized with [CircleAnnotation](../circleannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) override | Select square annotation if [AnnotationSelector](./) was initialized with [SquareAnnotation](../squareannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) override | Select ink annotation if [AnnotationSelector](./) was initialized with [InkAnnotation](../inkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) override | Select polyline annotation if [AnnotationSelector](./) was initialized with [PolylineAnnotation](../polylineannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) override | Select polygon annotation if [AnnotationSelector](./) was initialized with [PolygonAnnotation](../polygonannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) override | Select caret annotation if [AnnotationSelector](./) was initialized with [CaretAnnotation](../caretannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) override | Select stamp annotation if [AnnotationSelector](./) was initialized with [StampAnnotation](../stampannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) override | Select widget annotation if [AnnotationSelector](./) was initialized with [WidgetAnnotation](../widgetannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<WatermarkAnnotation\>) | Select watermark annotation if [AnnotationSelector](./) was initialized with [WatermarkAnnotation](../watermarkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) override | Select movie annotation if [AnnotationSelector](./) was initialized with [MovieAnnotation](../movieannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<RichMediaAnnotation\>) | Select movie annotation if [AnnotationSelector](./) was initialized with RichMedia annotation object. |
| [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) override | Select screen annotation if [AnnotationSelector](./) was initialized with [ScreenAnnotation](../screenannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<PDF3DAnnotation\>) | Select PDF3D annotation if [AnnotationSelector](./) was initialized with [PDF3DAnnotation](../pdf3dannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<ColorBarAnnotation\>) | Select ColorBar annotation if [AnnotationSelector](./) was initialized with ColorBar object. |
| [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) override | Selects the *trimMark*  if the [AnnotationSelector](./) was initialized with a [TrimMarkAnnotation](../trimmarkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) override | Selects the *bleedMark*  if the [AnnotationSelector](./) was initialized with a [BleedMarkAnnotation](../bleedmarkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) override | Selects the *registrationMark*  if the [AnnotationSelector](./) was initialized with a [RegistrationMarkAnnotation](../registrationmarkannotation/) object. |
| [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) override | Selects the *pageInformation*  if the [AnnotationSelector](./) was initialized with a [PageInformationAnnotation](../pageinformationannotation/) object. |
## See Also

* Class [IAnnotationVisitor](../iannotationvisitor/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
