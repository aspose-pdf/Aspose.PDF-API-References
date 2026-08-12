---
title: "Aspose::Pdf::Annotations::RedactionAnnotation-klass"
linktitle: "RedactionAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::RedactionAnnotation-klass. Representerar Redact-annotation i C++."
type: docs
weight: 9200
url: /sv/cpp/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class


Representerar Redact-anteckning.

```cpp
class RedactionAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [Flatten](./flatten/)() override | Plattar till annotation, d.v.s. tar bort annotationen och lägger till dess. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_BorderColor](./get_bordercolor/)() | Hämtar färg på kant som ritas när redigering inte är aktiv. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Hämtar standardutseendesträngen som ska användas vid formatering av texten. |
| [get_FillColor](./get_fillcolor/)() | Hämtar färg för att fylla annotation. |
| [get_FontSize](./get_fontsize/)() const | Hämtar teckenstorlek för OverlayText. |
| [get_OverlayText](./get_overlaytext/)() | Hämtar text att skriva ut på redigeringsannotation. |
| [get_QuadPoint](./get_quadpoint/)() | En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| [get_Repeat](./get_repeat/)() | Om true overlay text kommer att repated på annotationen. |
| [get_TextAlignment](./get_textalignment/)() | Hämtar. Justering av Overlay [Text](../../aspose.pdf.text/). |
| [Redact](./redact/)() | Plattar till annotation och redigerar sidinnehåll (d.v.s. tar bort text och bild under redigerad annotation) |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Document\>\&) | Konstruktor för [RedactionAnnotation](./). För användning i Generator. |
| [RedactionAnnotation](./redactionannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Konstruktor för RedactAnnotation. |
| [set_BorderColor](./set_bordercolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in färg på kant som ritas när redigering inte är aktiv. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Ställer in standardutseende-strängen som ska användas vid formatering av texten. |
| [set_FillColor](./set_fillcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in färg för att fylla annotation. |
| [set_FontSize](./set_fontsize/)(float) | Ställer in teckenstorlek för OverlayText. |
| [set_OverlayText](./set_overlaytext/)(const System::String\&) | Ställer in text att skriva ut på redigeringsannotation. |
| [set_QuadPoint](./set_quadpoint/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | En array med 8xN‑tal som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| [set_Repeat](./set_repeat/)(bool) | Om true overlay text kommer att repated på annotationen. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in. Justering av Overlay [Text](../../aspose.pdf.text/). |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
