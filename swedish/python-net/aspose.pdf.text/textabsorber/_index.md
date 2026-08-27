---
title: "TextAbsorber"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar ett absorber‑objekt för text.<br/>            Utför textutdragning och tillhandahåller åtkomst till resultatet via [text](/pdf/python-net/aspose.pdf.text/textabsorber/) objekt."
type: docs
weight: 320
url: /sv/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Representerar ett absorber‑objekt för text.<br/>            Utför textutdragning och tillhandahåller åtkomst till resultatet via [text](/pdf/python-net/aspose.pdf.text/textabsorber/) objekt.

TextAbsorber-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TextAbsorber() | Initierar en ny instans av [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Initierar en ny instans av TextAbsorber-klassen |
| TextAbsorber(extraction_options, text_search_options) | Initierar en ny instans av TextAbsorber-klassen |
| TextAbsorber(text_search_options) | Initierar en ny instans av TextAbsorber-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| text | Hämtar extraherad text som [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extraherar i PDF-dokumentet eller på sidan. |
| has_errors | Värdet indikerar om fel hittades under textutvinning.<br/>            Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestanda. |
| errors | Lista över [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) objekt. Den innehåller information om fel som hittades under textutvinning.<br/>            Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestanda. |
| extraction_options | Hämtar eller anger alternativ för textutvinning. |
| text_search_options | Hämtar eller anger alternativ för textsökning. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| visit(page) | Extraherar text på den angivna sidan |
| visit(form) | Extraherar text på den angivna XForm. |
| visit(pdf) | Extraherar text i det angivna dokumentet |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

