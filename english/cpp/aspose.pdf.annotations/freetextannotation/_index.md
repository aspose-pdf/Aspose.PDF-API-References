---
title: Aspose::Pdf::Annotations::FreeTextAnnotation class
linktitle: FreeTextAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FreeTextAnnotation class. Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible in C++.'
type: docs
weight: 4000
url: /cpp/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class


Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.

```cpp
class FreeTextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [FreeTextAnnotation](./freetextannotation/)(System::SharedPtr\<Document\>, System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Constructor to use with Generator. |
| [FreeTextAnnotation](./freetextannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Creates new FreeText annotation on the specified page. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Callout](./get_callout/)() | Array of point specifying callout line. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Gets the default appearance string to be used in formatting the text. |
| [get_DefaultAppearanceObject](./get_defaultappearanceobject/)() | Object which represents default appearance of FreeText annotation. |
| [get_DefaultStyle](./get_defaultstyle/)() | Gets a default style string. |
| [get_EndingStyle](./get_endingstyle/)() | Gets line ending style for line ending point. |
| [get_Intent](./get_intent/)() | Gets the intent of the free text annotation. |
| [get_Justification](./get_justification/)() | Gets or set a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [get_Rotate](./get_rotate/)() | Angle of annotation rotation. |
| [get_StartingStyle](./get_startingstyle/)() | Gets line ending style for line ending point. OThis property is obsolete, please use EndingStyle. |
| [get_TextRectangle](./get_textrectangle/)() | [Rectangle](../../aspose.pdf/rectangle/) describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed. |
| [get_TextStyle](./get_textstyle/)() | Gets style of the text in appearance. when text style is changed, text appearance is updated. |
| [set_Callout](./set_callout/)(System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Array of point specifying callout line. |
| [set_DefaultAppearance](./set_defaultappearance/)(System::String) | Sets the default appearance string to be used in formatting the text. |
| [set_DefaultStyle](./set_defaultstyle/)(System::String) | Sets a default style string. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Sets line ending style for line ending point. |
| [set_Intent](./set_intent/)(FreeTextIntent) | Sets the intent of the free text annotation. |
| [set_Justification](./set_justification/)(Aspose::Pdf::Annotations::Justification) | Gets or set a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [set_Rotate](./set_rotate/)(Rotation) | Angle of annotation rotation. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle. |
| [set_TextRectangle](./set_textrectangle/)(System::SharedPtr\<Rectangle\>) | [Rectangle](../../aspose.pdf/rectangle/) describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed. |
| [set_TextStyle](./set_textstyle/)(System::SharedPtr\<Aspose::Pdf::Annotations::TextStyle\>) | Sets style of the text in appearance. when text style is changed, text appearance is updated. |
| [SetTextStyle](./settextstyle/)(RichTextFontStyles, System::String, double, System::Drawing::Color) | Sets the formatting determined by the parameter textStyle for all annotation text. |
| [SetTextStyle](./settextstyle/)(int32_t, int32_t, RichTextFontStyles) | Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
