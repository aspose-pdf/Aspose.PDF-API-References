---
title: "Aspose::Pdf::Text::TextAbsorber klass"
linktitle: "TextAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextAbsorber-klass. Representerar ett absorberande objekt för text. Utför textutvinning och ger åtkomst till resultatet via TextAbsorber::Text-objekt i C++."
type: docs
weight: 3600
url: /sv/cpp/aspose.pdf.text/textabsorber/
---
## TextAbsorber class


Representerar ett absorberingsobjekt för en text. Utför textextraktion och ger åtkomst till resultatet via objektet [TextAbsorber::Text](../).

```cpp
class TextAbsorber : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Errors](./get_errors/)() const | Lista över [TextExtractionError](../textextractionerror/)-objekt. Den innehåller information om fel som hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [get_ExtractionOptions](./get_extractionoptions/)() | Hämtar alternativ för textutvinning. |
| [get_HasErrors](./get_haserrors/)() const | Värdet indikerar om fel hittades under textutvinning. Sökning efter fel utförs endast om TextSearchOptions.LogTextExtractionErrors = true; och det kan minska prestanda. |
| virtual [get_Text](./get_text/)() | Hämtar extraherad text som [TextAbsorber](./) extraherar i PDF-dokumentet eller på sidan. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Hämtar alternativ för textsökning. |
| virtual [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) | Ställer in alternativ för textutvinning. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Ställer in alternativ för textsökning. |
| [TextAbsorber](./textabsorber/)() | Initierar en ny instans av [TextAbsorber](./). |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&) | Initierar en ny instans av [TextAbsorber](./) med extraheringsalternativ. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TextAbsorber](./) med extraherings- och textsökningsalternativ. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Initierar en ny instans av [TextAbsorber](./) med textsökningsalternativ. |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extraherar text på den angivna sidan. |
| virtual [Visit](./visit/)(System::SharedPtr\<XForm\>) | Extraherar text på den angivna [XForm](../../aspose.pdf/xform/). |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>) | Extraherar text i det angivna dokumentet. |
## Anmärkningar


Objektet [TextAbsorber](./) används för att extrahera text från ett [Pdf](../../aspose.pdf/) dokument eller dokumentets sida.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
