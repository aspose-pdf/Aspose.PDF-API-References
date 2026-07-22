---
title: "Aspose::Pdf::Annotations::AnnotationSelector klass"
linktitle: "AnnotationSelector"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AnnotationSelector klass. Denna klass används för att välja annoteringar med hjälp av Visitor-mallidé i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class


Denna klass används för att välja annotationer med Visitor‑mallidé.

```cpp
class AnnotationSelector : public Aspose::Pdf::Annotations::IAnnotationVisitor
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AnnotationSelector](./annotationselector/)() | Initierar en ny instans av klassen [AnnotationSelector](./). |
| [AnnotationSelector](./annotationselector/)(const System::SharedPtr\<Annotation\>\&) | Initierar ett nytt [AnnotationSelector](./)-objekt. |
| [get_Selected](./get_selected/)() const | Listan över valda objekt. |
| [Visit](./visit/)(System::SharedPtr\<LinkAnnotation\>) override | Välj länkanotering om [AnnotationSelector](./) initierades med ett [LinkAnnotation](../linkannotation/)-objekt. |
| [Visit](./visit/)(System::SharedPtr\<FileAttachmentAnnotation\>) override | Välj bilaganotering om [AnnotationSelector](./) initierades med ett [FileAttachmentAnnotation](../fileattachmentannotation/)-objekt. |
| [Visit](./visit/)(System::SharedPtr\<TextAnnotation\>) override | Välj textannotering om [AnnotationSelector](./) initierades med ett [TextAnnotation](../textannotation/)-objekt. |
| [Visit](./visit/)(const System::SharedPtr\<RedactionAnnotation\>\&) | Välj raderingsannotering om [AnnotationSelector](./) initierades med ett RedactAnnotation-objekt. |
| [Visit](./visit/)(System::SharedPtr\<FreeTextAnnotation\>) override | Välj fritextannotering om [AnnotationSelector](./) initierades med ett [FreeTextAnnotation](../freetextannotation/)-objekt. |
| [Visit](./visit/)(System::SharedPtr\<HighlightAnnotation\>) override | Välj bilaganotering om [AnnotationSelector](./) initierades med ett [FreeTextAnnotation](../freetextannotation/)-objekt. |
| [Visit](./visit/)(System::SharedPtr\<UnderlineAnnotation\>) override | Välj understrykningannotering om [AnnotationSelector](./) initierades med ett [UnderlineAnnotation](../underlineannotation/)-objekt. |
| [Visit](./visit/)(System::SharedPtr\<StrikeOutAnnotation\>) override | Välj strikeOut-annotation om [AnnotationSelector](./) initierades med [StrikeOutAnnotation](../strikeoutannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<SquigglyAnnotation\>) override | Välj squiggly-annotation om [AnnotationSelector](./) initierades med [SquigglyAnnotation](../squigglyannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<PopupAnnotation\>) override | Välj popup-annotation om [AnnotationSelector](./) initierades med [PopupAnnotation](../popupannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<LineAnnotation\>) override | Välj line-annotation om [AnnotationSelector](./) initierades med [LineAnnotation](../lineannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<CircleAnnotation\>) override | Välj circle-annotation om [AnnotationSelector](./) initierades med [CircleAnnotation](../circleannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<SquareAnnotation\>) override | Välj square-annotation om [AnnotationSelector](./) initierades med [SquareAnnotation](../squareannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<InkAnnotation\>) override | Välj ink-annotation om [AnnotationSelector](./) initierades med [InkAnnotation](../inkannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<PolylineAnnotation\>) override | Välj polyline-annotation om [AnnotationSelector](./) initierades med [PolylineAnnotation](../polylineannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<PolygonAnnotation\>) override | Välj polygon-annotation om [AnnotationSelector](./) initierades med [PolygonAnnotation](../polygonannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<CaretAnnotation\>) override | Välj caret-annotation om [AnnotationSelector](./) initierades med [CaretAnnotation](../caretannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<StampAnnotation\>) override | Välj stamp-annotation om [AnnotationSelector](./) initierades med [StampAnnotation](../stampannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<WidgetAnnotation\>) override | Välj widget-annotation om [AnnotationSelector](./) initierades med [WidgetAnnotation](../widgetannotation/) objekt. |
| [Visit](./visit/)(const System::SharedPtr\<WatermarkAnnotation\>\&) | Välj watermark-annotation om [AnnotationSelector](./) initierades med [WatermarkAnnotation](../watermarkannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<MovieAnnotation\>) override | Välj movie-annotation om [AnnotationSelector](./) initierades med [MovieAnnotation](../movieannotation/) objekt. |
| [Visit](./visit/)(const System::SharedPtr\<RichMediaAnnotation\>\&) | Välj movie-annotation om [AnnotationSelector](./) initierades med RichMedia-annotation objekt. |
| [Visit](./visit/)(System::SharedPtr\<ScreenAnnotation\>) override | Välj screen-annotation om [AnnotationSelector](./) initierades med [ScreenAnnotation](../screenannotation/) objekt. |
| [Visit](./visit/)(const System::SharedPtr\<PDF3DAnnotation\>\&) | Välj PDF3D-annotation om [AnnotationSelector](./) initierades med [PDF3DAnnotation](../pdf3dannotation/) objekt. |
| [Visit](./visit/)(const System::SharedPtr\<ColorBarAnnotation\>\&) | Välj ColorBar-annotation om [AnnotationSelector](./) initierades med ColorBar objekt. |
| [Visit](./visit/)(System::SharedPtr\<TrimMarkAnnotation\>) override | Väljer *trimMark* om [AnnotationSelector](./) initierades med en [TrimMarkAnnotation](../trimmarkannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<BleedMarkAnnotation\>) override | Väljer *bleedMark* om [AnnotationSelector](./) initierades med en [BleedMarkAnnotation](../bleedmarkannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<RegistrationMarkAnnotation\>) override | Väljer *registrationMark* om [AnnotationSelector](./) initierades med en [RegistrationMarkAnnotation](../registrationmarkannotation/) objekt. |
| [Visit](./visit/)(System::SharedPtr\<PageInformationAnnotation\>) override | Väljer *pageInformation* om [AnnotationSelector](./) initierades med en [PageInformationAnnotation](../pageinformationannotation/) objekt. |
## Se även

* Class [IAnnotationVisitor](../iannotationvisitor/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
