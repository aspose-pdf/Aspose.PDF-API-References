---
title: "Aspose::Pdf::Annotations::LineAnnotation class"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::LineAnnotation class. Klass som representerar linjeannotation i C++."
type: docs
weight: 5700
url: /sv/cpp/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class


Klass som representerar linjeanteckning.

```cpp
class LineAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökare för annoteringsbearbetning. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Uppdaterar start- och slutpunkterna enligt matrisomvandlingen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_CaptionOffset](./get_captionoffset/)() | Hämtar bildtextens förskjutning från dess normala position. |
| [get_CaptionPosition](./get_captionposition/)() | Hämtar annoteringens bildtextposition. |
| [get_Ending](./get_ending/)() | Hämtar linjens slutpunkt. |
| [get_EndingStyle](./get_endingstyle/)() | Hämtar avslutningsstil för linjens slutpunkt. |
| [get_Intent](./get_intent/)() | Hämtar avsikten med linjeannoteringen. |
| [get_InteriorColor](./get_interiorcolor/)() | Hämtar interiorfärgen för annoteringen. |
| [get_LeaderLine](./get_leaderline/)() | Hämtar ledarlinjens längd. |
| [get_LeaderLineExtension](./get_leaderlineextension/)() | Hämtar längden på ledarlinjeutökningen. |
| [get_LeaderLineOffset](./get_leaderlineoffset/)() | Hämtar ledarlinjens förskjutning. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) enheter som specificeras för denna annotering. |
| [get_ShowCaption](./get_showcaption/)() | Hämtar booleskt flagga som bestämmer om innehållet ska visas som bildtext. |
| [get_Starting](./get_starting/)() | Hämtar linjens startpunkt. |
| [get_StartingStyle](./get_startingstyle/)() | Hämtar linjeändningsstil för linjens startpunkt. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Konstruktor för användning med Generator. |
| [LineAnnotation](./lineannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) | Skapar ny linjeannotation på den angivna sidan. |
| [set_CaptionOffset](./set_captionoffset/)(const System::SharedPtr\<Point\>\&) | Ställer in bildtextens förskjutning från dess normala position. |
| [set_CaptionPosition](./set_captionposition/)(Aspose::Pdf::Annotations::CaptionPosition) | Ställer in annoteringens bildtextposition. |
| [set_Ending](./set_ending/)(const System::SharedPtr\<Point\>\&) | Ställer in linjens slutpunkt. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Ställer in avslutningsstil för linjens slutpunkt. |
| [set_Intent](./set_intent/)(LineIntent) | Ställer in avsikten med linjeannoteringen. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in annoteringens interiörfärg. |
| [set_LeaderLine](./set_leaderline/)(double) | Ställer in ledarlinjens längd. |
| [set_LeaderLineExtension](./set_leaderlineextension/)(double) | Ställer in längden på ledarlinjeutökningen. |
| [set_LeaderLineOffset](./set_leaderlineoffset/)(double) | Ställer in ledarlinjens förskjutning. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | [Measure](../measure/) enheter som specificeras för denna annotering. |
| [set_ShowCaption](./set_showcaption/)(bool) | Ställer in en boolesk flagga som bestämmer om innehållet ska visas som bildtext. |
| [set_Starting](./set_starting/)(const System::SharedPtr\<Point\>\&) | Ställer in linjens startpunkt. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Ställer in linjeändningsstil för linjens startpunkt. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
