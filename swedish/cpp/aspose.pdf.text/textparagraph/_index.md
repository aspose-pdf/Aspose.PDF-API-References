---
title: "Aspose::Pdf::Text::TextParagraph klass"
linktitle: "TextParagraph"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextParagraph klass. Representerar textparagrafer som flerradigt textobjekt i C++."
type: docs
weight: 4800
url: /sv/cpp/aspose.pdf.text/textparagraph/
---
## TextParagraph class


Representerar textstycken som ett flerradigt textobjekt.

```cpp
class TextParagraph : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AppendLine](./appendline/)(const System::String\&) | Lägger till en textrad. |
| [AppendLine](./appendline/)(const System::String\&, float) | Lägger till en textrad. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&) | Lägger till en textrad med parametrar för texttillstånd. |
| [AppendLine](./appendline/)(const System::String\&, const System::SharedPtr\<TextState\>\&, float) | Lägger till en textrad med parametrar för texttillstånd. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&) | Lägger till en textrad med parametrar för texttillstånd. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&) | Lägger till en textrad med parametrar för texttillstånd. |
| [AppendLine](./appendline/)(const System::SharedPtr\<TextFragment\>\&, const System::SharedPtr\<TextState\>\&, float) | Lägger till en textrad med parametrar för texttillstånd. |
| [BeginEdit](./beginedit/)() | Påbörjar redigeringen av [TextParagraph](./). |
| [EndEdit](./endedit/)() | Avslutar redigeringen av [TextParagraph](./). |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Hämtar indenteringsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [get_FormattingOptions](./get_formattingoptions/)() const | Hämtar formateringsalternativ. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Hämtar horisontell justering för texten i paragrafens [Rectangle](../../aspose.pdf/rectangle/). |
| [get_Justify](./get_justify/)() | Hämtar värdet om texten är justerad. |
| [get_Margin](./get_margin/)() const | Hämtar utfyllnaden. |
| [get_Position](./get_position/)() const | Hämtar positionen för paragrafen. |
| [get_Rectangle](./get_rectangle/)() const | Hämtar rektangeln för paragrafen. |
| [get_Rotation](./get_rotation/)() const | Hämtar rotationsvinkeln i grader. |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Hämtar indenteringsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [get_TextRectangle](./get_textrectangle/)() | Hämtar rektangeln för texten placerad i paragrafen. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Hämtar vertikal justering för texten i paragrafens [Rectangle](../../aspose.pdf/rectangle/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Sätter indenteringsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [set_FormattingOptions](./set_formattingoptions/)(const System::SharedPtr\<TextFormattingOptions\>\&) | Sätter formateringsalternativ. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sätter horisontell justering för texten i paragrafens [Rectangle](../../aspose.pdf/rectangle/). |
| [set_Justify](./set_justify/)(bool) | Sätter värdet om texten är justerad. |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Sätter utfyllnaden. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Ställer in positionen för stycket. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in rektangeln för stycket. |
| [set_Rotation](./set_rotation/)(double) | Ställer in rotationsvinkeln i grader. |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Sätter indenteringsvärdet för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med värdet FormattingOptions.SubsequentLinesIndent. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Ställer in vertikal justering för texten inne i styckets [Rectangle](../../aspose.pdf/rectangle/). |
| [TextParagraph](./textparagraph/)() | Skapar [TextParagraph](./)-objekt. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
