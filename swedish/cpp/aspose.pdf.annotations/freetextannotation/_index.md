---
title: "Aspose::Pdf::Annotations::FreeTextAnnotation-klass"
linktitle: "FriTextAnteckning"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::FreeTextAnnotation-klass. Representerar en fri textanteckning som visar text direkt på sidan. Till skillnad från en vanlig textanteckning har en fri textanteckning inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig i C++."
type: docs
weight: 4000
url: /sv/cpp/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class


Representerar en fri textanteckning som visar text direkt på sidan. Till skillnad från en vanlig textanteckning har en fri textanteckning inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig.

```cpp
class FreeTextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Konstruktor att använda med Generator. |
| [FreeTextAnnotation](./freetextannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Skapar ny FriText-anteckning på den angivna sidan. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Callout](./get_callout/)() | Matris av punkter som specificerar anropslinjen. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Hämtar standardutseendesträngen som ska användas vid formatering av texten. |
| [get_DefaultAppearanceObject](./get_defaultappearanceobject/)() | Objekt som representerar standardutseendet för FreeText-annotation. |
| [get_DefaultStyle](./get_defaultstyle/)() | Hämtar en standardstilssträng. |
| [get_EndingStyle](./get_endingstyle/)() | Hämtar linjeändningsstil för linjeändningspunkt. |
| [get_Intent](./get_intent/)() | Hämtar avsikten med free text-annotation. |
| [get_Justification](./get_justification/)() | Hämtar eller anger en kod som specificerar formen av quadding (justering) som ska användas vid visning av annotationens text. |
| [get_Rotate](./get_rotate/)() | Vinkel för annotationens rotation. |
| [get_StartingStyle](./get_startingstyle/)() | Hämtar linjeändningsstil för linjeändningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle. |
| [get_TextRectangle](./get_textrectangle/)() | [Rectangle](../../aspose.pdf/rectangle/) som beskriver de numeriska skillnaderna mellan två rektanglar: Rect-posten i annotationen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annotationens text ska visas. |
| [get_TextStyle](./get_textstyle/)() | Hämtar stil för texten i utseendet. När textstilen ändras uppdateras textens utseende. |
| [set_Callout](./set_callout/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Matris av punkter som specificerar anropslinjen. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::String\&) | Ställer in standardutseende-strängen som ska användas vid formatering av texten. |
| [set_DefaultStyle](./set_defaultstyle/)(const System::String\&) | Ställer in en standardstilssträng. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Ställer in linjeändningsstil för linjeändningspunkt. |
| [set_Intent](./set_intent/)(FreeTextIntent) | Ställer in avsikten för free text-annotation. |
| [set_Justification](./set_justification/)(Aspose::Pdf::Annotations::Justification) | Hämtar eller anger en kod som specificerar formen av quadding (justering) som ska användas vid visning av annotationens text. |
| [set_Rotate](./set_rotate/)(Rotation) | Vinkel för annotationens rotation. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Ställer in linjeändningsstil för linjeändningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle. |
| [set_TextRectangle](./set_textrectangle/)(const System::SharedPtr\<Rectangle\>\&) | [Rectangle](../../aspose.pdf/rectangle/) som beskriver de numeriska skillnaderna mellan två rektanglar: Rect-posten i annotationen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annotationens text ska visas. |
| [set_TextStyle](./set_textstyle/)(const System::SharedPtr\<Aspose::Pdf::Annotations::TextStyle\>\&) | Ställer in stil för texten i utseendet. När textstilen ändras uppdateras textens utseende. |
| [SetTextStyle](./settextstyle/)(RichTextFontStyles, const System::String\&, double, System::Drawing::Color) | Ställer in formateringen som bestäms av parametern textStyle för all annotationstext. |
| [SetTextStyle](./settextstyle/)(int32_t, int32_t, RichTextFontStyles) | Ställer in formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
