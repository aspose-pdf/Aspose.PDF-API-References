---
title: "Aspose::Pdf::Text::TextFragmentAbsorber-klass"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragmentAbsorber-klass. Representerar ett absorberingsobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via TextFragmentAbsorber::TextFragments-samlingen i C++."
type: docs
weight: 4400
url: /sv/cpp/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class


Representerar ett absorberingsobjekt för textfragment. Utför textsökning och ger åtkomst till sökresultat via samlingen [TextFragmentAbsorber::TextFragments](../).

```cpp
class TextFragmentAbsorber : public Aspose::Pdf::Text::TextAbsorber
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&) | Tillämpar teckensnitt för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det på samma sätt som loopning. |
| [ApplyForAllFragments](./applyforallfragments/)(float) | Tillämpar teckenstorlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det på liknande sätt som loopning. |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&, float) | Tillämpar teckensnitt och storlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberades. Annars fungerar det på liknande sätt som loopning. |
| [get_Errors](./get_errors/)() | Lista över [TextExtractionError](../textextractionerror/)-objekt. Den innehåller information om fel som hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [get_ExtractionOptions](./get_extractionoptions/)() override | Hämtar alternativ för textutvinning. |
| [get_HasErrors](./get_haserrors/)() | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| [get_Phrase](./get_phrase/)() const | Hämtar frasen som [TextFragmentAbsorber](./) söker efter i PDF-dokumentet eller på sidan. |
| [get_RegexResults](./get_regexresults/)() const | Hämtar en ordbok med sök förekomster som presenteras med [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/)-klassen som nyckel och [TextFragment](../textfragment/)-som värde. |
| [get_Text](./get_text/)() override | Hämtar den extraherade texten som [TextAbsorber](../textabsorber/) extraherar i PDF-dokumentet eller på sidan. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Hämtar alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [get_TextFragments](./get_textfragments/)() | Hämtar en samling av sök förekomster som presenteras med [TextFragment](../textfragment/)-objekt. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Hämtar alternativ för textutbyte. Alternativen definierar beteendet när fragmenttext ersätts med kortare/längre. |
| [get_TextSearchOptions](./get_textsearchoptions/)() override | Hämtar sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&) | Tar bort all text från den angivna sidan. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Tar bort text inom den angivna rektangeln från den angivna sidan. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Document\>\&) | Tar bort all text från dokumentet. |
| [Reset](./reset/)() | Rensar TextFragments-samlingen för detta [TextFragmentAbsorber](./)-objekt. |
| [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) override | Ställer in alternativ för textutvinning. |
| [set_Phrase](./set_phrase/)(const System::String\&) | Ställer in frasen som [TextFragmentAbsorber](./) söker efter i PDF-dokumentet eller på sidan. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Ställer in alternativ för textredigering. Alternativen definierar särskilt beteende när den begärda symbolen inte kan skrivas med teckensnittet. |
| [set_TextFragments](./set_textfragments/)(const System::SharedPtr\<TextFragmentCollection\>\&) | Hämtar en samling av sök förekomster som presenteras med [TextFragment](../textfragment/)-objekt. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Ställer in alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts med kortare/längre text. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) override | Ställer in sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. |
| [TextFragmentAbsorber](./textfragmentabsorber/)() | Initierar en ny instans av [TextFragmentAbsorber](./) som utför sökning av alla textsegment i dokumentet eller på sidan. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./) med alternativ för textredigering, som utför sökning av alla textsegment i dokumentet eller på sidan. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för det angivna [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/)-klassobjektet. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen och alternativ för textsökning. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen, alternativ för textsökning och alternativ för textredigering. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen och alternativ för textredigering. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Initierar en ny instans av [TextFragmentAbsorber](./)-klassen för den angivna textfrasen och alternativ för textredigering. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) override | Utför sökning på den angivna sidan. |
| [Visit](./visit/)(System::SharedPtr\<Document\>) override | Utför sökning i det angivna dokumentet. |
| [Visit](./visit/)(System::SharedPtr\<XForm\>) override | Utför sökning på det angivna formulärobjektet. |
## Anmärkningar


Objektet [TextFragmentAbsorber](./) används i princip i textsökningsscenario. När sökningen är slutförd representeras förekomsterna med [TextFragment](../textfragment/)-objekt som samlingen [TextFragmentAbsorber::TextFragments](../) innehåller. [TextFragment](../textfragment/)-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).
## Se även

* Class [TextAbsorber](../textabsorber/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
