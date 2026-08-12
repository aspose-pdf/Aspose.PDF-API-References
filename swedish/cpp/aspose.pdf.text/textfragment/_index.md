---
title: "Aspose::Pdf::Text::TextFragment-klass"
linktitle: "TextFragment"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragment-klass. Representerar ett fragment av Pdf-text i C++."
type: docs
weight: 4300
url: /sv/cpp/aspose.pdf.text/textfragment/
---
## TextFragment class


Representerar ett fragment av [Pdf](../../aspose.pdf/) text.

```cpp
class TextFragment : public Aspose::Pdf::BaseParagraph
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klona fragmentet. |
| virtual [CloneWithSegments](./clonewithsegments/)() | Klona fragmentet med alla segment. |
| [get_BaselinePosition](./get_baselineposition/)() | Hämtar textposition för text, representerad med [TextFragment](./)-objekt. YIndent i [Position](../position/)-strukturen representerar baslinjekoordinationen för textfragmentet. |
| [get_EndNote](./get_endnote/)() const | Hämtar paragrafens slutnotering (endast för pdf-generering). |
| [get_FootNote](./get_footnote/)() const | Hämtar paragrafens fotnot (endast för pdf-generering). |
| [get_Form](./get_form/)() const | Hämtar formulärobjektet som innehåller [TextFragment](./). |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Hämtar en horisontell justering av textfragmentet. |
| [get_Page](./get_page/)() const | Hämtar sidan som innehåller [TextFragment](./). |
| [get_Position](./get_position/)() | Hämtar textposition för text som representeras med [TextFragment](./)-objektet. |
| [get_Rectangle](./get_rectangle/)() | Hämtar rektangeln för [TextFragment](./). |
| [get_ReplaceOptions](./get_replaceoptions/)() const | Hämtar alternativ för textutbyte. Alternativen definierar beteendet när fragmenttext ersätts med kortare/längre. |
| [get_Segments](./get_segments/)() const | Hämtar textsegment för aktuell [TextFragment](./). |
| [get_Text](./get_text/)() | Hämtar [System::String](../../system/string/)-textobjektet som [TextFragment](./)-objektet representerar. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Hämtar alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [get_TextState](./get_textstate/)() | Hämtar texttillstånd för den text som [TextFragment](./)-objektet representerar. |
| [get_VerticalAlignment](./get_verticalalignment/)() override | Hämtar en vertikal justering av textfragmentet. |
| [get_WrapLinesCount](./get_wraplinescount/)() const | Hämtar antal radbrytningar för detta stycke(för pdf-generering endast) |
| [IsolateTextSegments](./isolatetextsegments/)(int32_t, int32_t) | Hämtar [TextSegment](../textsegment/)(er) som representerar den angivna delen av [TextFragment](./)-texten. |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Hämtar textposition för text, representerad med [TextFragment](./)-objekt. YIndent i [Position](../position/)-strukturen representerar baslinjekoordinationen för textfragmentet. |
| [set_EndNote](./set_endnote/)(const System::SharedPtr\<Note\>\&) | Ställer in slutnot för stycket.(för pdf-generering endast) |
| [set_FootNote](./set_footnote/)(const System::SharedPtr\<Note\>\&) | Ställer in fotnot för stycket.(för pdf-generering endast) |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Ställer in en horisontell justering av textfragmentet. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) override | Ställer in fragmentets hyperlänk. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Ställer in textposition för text som representeras med [TextFragment](./)-objektet. |
| [set_Segments](./set_segments/)(const System::SharedPtr\<TextSegmentCollection\>\&) | Hämtar textsegment för aktuell [TextFragment](./). |
| [set_Text](./set_text/)(const System::String\&) | Ställer in [System::String](../../system/string/)-textobjektet som [TextFragment](./)-objektet representerar. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Ställer in alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) override | Ställer in en vertikal justering av textfragmentet. |
| [set_WrapLinesCount](./set_wraplinescount/)(int32_t) | Ställer in antal radbrytningar för detta stycke(för pdf-generering endast) |
| [TextFragment](./textfragment/)() | Initierar en ny instans av [TextFragment](./)-objektet. |
| [TextFragment](./textfragment/)(const System::SharedPtr\<TabStops\>\&) | Initierar en ny instans av [TextFragment](./)-objektet med fördefinierade [TabStops](../tabstops/)-positioner. |
| [TextFragment](./textfragment/)(const System::String\&) | Skapar ett [TextFragment](./)-objekt med ett enda [TextSegment](../textsegment/)-objekt inuti. Anger textsträngen i segmentet. |
| [TextFragment](./textfragment/)(const System::String\&, const System::SharedPtr\<TabStops\>\&) | Skapar ett [TextFragment](./)-objekt med ett enda [TextSegment](../textsegment/)-objekt inuti och fördefinierade [TabStops](../tabstops/)-positioner. |
## Anmärkningar


Med några ord innehåller [TextFragment](./)-objektet en lista med [TextSegment](../textsegment/)-objekt.

I detalj: [Text](../) i pdf-dokument i [Aspose::Pdf](../../aspose.pdf/) representeras av två grundläggande objekt: [TextFragment](./) och [TextSegment](../textsegment/)

Skillnaderna mellan dem är mest kontextberoende.

Låt oss betrakta följande scenario. Användaren söker texten "hello world" för att arbeta med den, ändra dess egenskaper, titta osv.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
Den fysiska representationen av pdf-text är mycket komplex. Texten "hello world" kan bestå av flera fysiskt oberoende textsegment.

[Aspose.Pdf](../../aspose.pdf/) textmodellen fastställer i princip att [TextFragment](./)-objektet tillhandahåller en enda logisk operationsuppsättning över en fysisk [TextSegment](../textsegment/)-objektuppsättning som representerar användarens fråga.

I textsökningsscenario är [TextFragment](./) en logisk "hello world"-textrepresentation, och [TextSegment](../textsegment/)-objektsamlingen representerar alla fysiska segment som bygger upp "hello world"-textobjektet.

Alltså är [TextFragment](./) nära den logiska textrepresentationen. Och [TextSegment](../textsegment/) är nära den fysiska textrepresentationen.

Uppenbarligen kan varje [TextSegment](../textsegment/)-objekt ha sina egna teckensnitt, färgning och placeringsegenskaper.

[TextFragment](./) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](../textsegment/) objects are accessible and users are able to operate with [TextSegment](../textsegment/) objects independently.

[Note](../../aspose.pdf/note/) that changing [TextFragment](./) properties may change inner [Segments](../) collection because [TextFragment](./) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [Segments](../) collection unchanged, please change inner segments individually. 
## Se även

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
