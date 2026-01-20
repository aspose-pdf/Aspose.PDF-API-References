---
title: Aspose::Pdf::Annotations::RedactionAnnotation class
linktitle: RedactionAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::RedactionAnnotation class. Represents Redact annotation in C++.'
type: docs
weight: 9200
url: /cpp/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class


Represents Redact annotation.

```cpp
class RedactionAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [Flatten](./flatten/)() override | Flattens annotation i.e. removes annotation and adds its. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_BorderColor](./get_bordercolor/)() | Gets color of border which is drawn when redaction is not active. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Gets the default appearance string to be used in formatting the text. |
| [get_FillColor](./get_fillcolor/)() | Gets color to fill annotation. |
| [get_FontSize](./get_fontsize/)() const | Gets font size for OverlayText. |
| [get_OverlayText](./get_overlaytext/)() | Gets text to print on redact annotation. |
| [get_QuadPoint](./get_quadpoint/)() | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [get_Repeat](./get_repeat/)() | If true overlay text will be repated on the annotation. |
| [get_TextAlignment](./get_textalignment/)() | Gets. Alignment of Overlay [Text](../../aspose.pdf.text/). |
| [Redact](./redact/)() | Flattens annotation and redacts page contents (i.e. removes text and image under redacted annotation) |
| [RedactionAnnotation](./redactionannotation/)(System::SharedPtr\<Document\>) | Constructor for [RedactionAnnotation](./). For using in Generator. |
| [RedactionAnnotation](./redactionannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for RedactAnnotation. |
| [set_BorderColor](./set_bordercolor/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets color of border which is drawn when redaction is not active. |
| [set_DefaultAppearance](./set_defaultappearance/)(System::String) | Sets the default appearance string to be used in formatting the text. |
| [set_FillColor](./set_fillcolor/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets color to fill annotation. |
| [set_FontSize](./set_fontsize/)(float) | Sets font size for OverlayText. |
| [set_OverlayText](./set_overlaytext/)(System::String) | Sets text to print on redact annotation. |
| [set_QuadPoint](./set_quadpoint/)(System::ArrayPtr\<System::SharedPtr\<Point\>\>) | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [set_Repeat](./set_repeat/)(bool) | If true overlay text will be repated on the annotation. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets. Alignment of Overlay [Text](../../aspose.pdf.text/). |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
