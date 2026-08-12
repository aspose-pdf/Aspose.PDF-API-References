---
title: "Aspose::Pdf::Text::TextSegment klass"
linktitle: "TextSegment"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextSegment klass. Representerar ett segment av Pdf‑text i C++."
type: docs
weight: 5100
url: /sv/cpp/aspose.pdf.text/textsegment/
---
## TextSegment class


Representerar ett segment av [Pdf](../../aspose.pdf/) text.

```cpp
class TextSegment : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BaselinePosition](./get_baselineposition/)() const | Hämtar textposition för text, representerad med [TextSegment](./)-objektet. YIndent i [Position](../position/)-strukturen representerar baslinjekoordinationen för textsegmentet. |
| [get_Characters](./get_characters/)() | Hämtar en samling av [CharInfo](../charinfo/)-objekt som representerar information om tecken i textsegmentet. |
| [get_EndCharIndex](./get_endcharindex/)() const | Hämtar slutteckenindex för det aktuella segmentet i show‑text‑operatorn (Tj, TJ). |
| [get_Hyperlink](./get_hyperlink/)() const | Hämtar segmentets hyperlänk (för pdf‑generator). |
| [get_Position](./get_position/)() const | Hämtar textposition för text, representerad med [TextSegment](./)-objektet. |
| [get_Rectangle](./get_rectangle/)() | Hämtar rektangeln för [TextSegment](./). |
| [get_StartCharIndex](./get_startcharindex/)() const | Hämtar startteckenindex för det aktuella segmentet i show‑text‑operatorn (Tj, TJ). |
| [get_Text](./get_text/)() const | Hämtar [System::String](../../system/string/) textobjekt som [TextSegment](./)-objektet representerar. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Hämtar alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [get_TextState](./get_textstate/)() const | Hämtar texttillstånd för den text som [TextSegment](./)-objektet representerar. |
| static [MyHtmlEncode](./myhtmlencode/)(const System::String\&) | Kodar strängen som HTML. |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Hämtar textposition för text, representerad med [TextSegment](./)-objektet. YIndent i [Position](../position/)-strukturen representerar baslinjekoordinationen för textsegmentet. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Ställer in segmentets hyperlänk (för PDF‑generator). |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Hämtar textposition för text, representerad med [TextSegment](./)-objektet. |
| [set_Text](./set_text/)(const System::String\&) | Ställer in [System::String](../../system/string/) textobjekt som [TextSegment](./)-objektet representerar. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Ställer in alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Ställer in texttillstånd för den text som [TextSegment](./)-objektet representerar. |
| [TextSegment](./textsegment/)() | Skapar [TextSegment](./)-objekt. |
| [TextSegment](./textsegment/)(const System::String\&) | Skapar [TextSegment](./)-objekt. |
## Anmärkningar


Med några ord är [TextSegment](./)-objekt barn till [TextFragment](../textfragment/)-objektet.

I detalj:

[Text](../) of pdf document in [Aspose::Pdf](../../aspose.pdf/) is represented by two basic objects: [TextFragment](../textfragment/) and [TextSegment](./)

Skillnaderna mellan dem är mest kontextberoende.

Låt oss betrakta följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta osv.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
Den fysiska representationen av pdf-text är mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment.

[Aspose.Pdf](../../aspose.pdf/)-textmodellen fastställer i princip att [TextFragment](../textfragment/)-objektet tillhandahåller en enda logisk operationsuppsättning över den fysiska uppsättningen av [TextSegment](./)-objekt som representerar användarens fråga.

I textsökningsscenario är [TextFragment](../textfragment/) en logisk "hello world"-textrepresentation, och samlingen av [TextSegment](./)-objekt representerar alla fysiska segment som bygger upp "hello world"-textobjektet.

Alltså är [TextFragment](../textfragment/) nära den logiska textrepresentationen. Och [TextSegment](./) är nära den fysiska textrepresentationen.

Uppenbarligen kan varje [TextSegment](./)-objekt ha sin egen teckensnitt, färgning och placerings‑egenskaper.

[TextFragment](../textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](./) objects are accessible and users are able to operate with [TextSegment](./) objects independently. 
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
