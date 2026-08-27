---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar ett absorber‑objekt för textfragment.<br/>            Utför textsökning och tillhandahåller åtkomst till sökresultat via [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) samling."
type: docs
weight: 400
url: /sv/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Representerar ett absorber‑objekt för textfragment.<br/>            Utför textsökning och tillhandahåller åtkomst till sökresultat via [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) samling.

TextFragmentAbsorber-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TextFragmentAbsorber() | Initierar en ny instans av [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) som utför sökning av alla textsegment i dokumentet eller sidan. |
| TextFragmentAbsorber(text_edit_options) | Initierar en ny instans av klassen TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Initierar en ny instans av klassen TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Initierar en ny instans av klassen TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Initierar en ny instans av klassen TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Initierar en ny instans av klassen TextFragmentAbsorber |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| text | Hämtar extraherad text som [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extraherar i PDF-dokumentet eller på sidan. |
| has_errors | Värdet indikerar om fel hittades under textutvinning.<br/>            Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestanda. |
| errors | Lista över [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) objekt. Den innehåller information om fel som hittades under textutvinning.<br/>            Sökning efter fel kommer endast att utföras om TextSearchOptions.LogTextExtractionErrors = true; Och det kan minska prestanda. |
| extraction_options | Hämtar eller anger alternativ för textutvinning. |
| text_search_options | Hämtar eller anger sökalternativ. Alternativen möjliggör sökning med reguljära uttryck. |
| text_fragments | Hämtar en samling av sökförekomster som presenteras med [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) objekt. |
| phrase | Hämtar eller anger fras som [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) söker i PDF-dokumentet eller på sidan. |
| text_edit_options | Hämtar eller anger alternativ för textredigering. Alternativen definierar speciellt beteende när begärt tecken inte kan skrivas med teckensnittet. |
| text_replace_options | Hämtar eller anger alternativ för textersättning. Alternativen definierar beteende när fragmenttext ersätts till kortare/längre. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| visit(page) | Utför sökning på den angivna sidan. |
| visit(pdf) | Utför sökning i det angivna dokumentet. |
| visit(x_form) | Utför sökning på det angivna formulärobjektet. |
| apply_for_all_fragments(font) | Tillämpar teckensnitt för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning. |
| apply_for_all_fragments(font_size) | Tillämpar teckenstorlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning. |
| apply_for_all_fragments(font, font_size) | Tillämpar teckensnitt och storlek för alla textfragment som absorberats. Det fungerar snabbare än att loopa igenom fragmenten om alla fragment på sidan/sidorna absorberats. Annars fungerar det på liknande sätt som loopning. |
| remove_all_text(page) | Tar bort all text från den angivna sidan. |
| remove_all_text(page, rect) | Tar bort text inom den angivna rektangeln från den angivna sidan. |
| remove_all_text(document) | Tar bort all text från dokumentet. |
| reset() | Rensar TextFragments-samlingen för detta [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) objekt. |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

