---
title: "Aspose::Pdf::Annotations::WatermarkAnnotation klass"
linktitle: "WatermarkAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::WatermarkAnnotation klass. Klass beskriver Watermark‑annotationobjekt i C++."
type: docs
weight: 11700
url: /sv/cpp/aspose.pdf.annotations/watermarkannotation/
---
## WatermarkAnnotation class


Klassen beskriver [Watermark](../../aspose.pdf/watermark/) annotation‑objekt.

```cpp
class WatermarkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Använd besökare för annotation. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Åsidosätter definitionen i basklassen med en tom kropp. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar annotationstyp. |
| [get_FixedPrint](./get_fixedprint/)() | Fuxed utskriftsobjekt för [Watermark](../../aspose.pdf/watermark/) annotation. |
| [get_Opacity](./get_opacity/)() const | Hämtar opaciteten för annotationen. |
| [set_Opacity](./set_opacity/)(double) | Ställer in opaciteten för annotationen. |
| [SetText](./settext/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Ange text för annotationen. |
| [SetTextAndState](./settextandstate/)(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<Text::TextState\>\&) | Ange text för annotationen. |
| [WatermarkAnnotation](./watermarkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för [Watermark](../../aspose.pdf/watermark/) annotation‑klass. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
