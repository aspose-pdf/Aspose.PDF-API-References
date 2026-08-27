---
title: "TextFragment"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar ett fragment av Pdf‑text."
type: docs
weight: 390
url: /sv/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

Representerar ett fragment av Pdf‑text.

TextFragment-typen visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TextFragment() | Initierar en ny instans av [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) objektet. |
| TextFragment(tab_stops) | Initierar en ny instans av TextFragment-klassen |
| TextFragment(text) | Initierar en ny instans av TextFragment-klassen |
| TextFragment(text, tab_stops) | Initierar en ny instans av TextFragment-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| vertical_alignment | Hämtar eller anger en vertikal justering av textfragmentet. |
| horizontal_alignment | Hämtar eller anger en horisontell justering av textfragmentet. |
| margin | Hämtar eller anger en yttre marginal för stycket (för pdf‑generering) |
| is_first_paragraph_in_column | Hämtar eller anger ett bool‑värde som indikerar om detta stycke kommer att vara i nästa kolumn.<br/>            Standard är false.(för pdf‑generering) |
| is_kept_with_next | Hämtar eller anger ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke.<br/>            Standard är false.(för pdf‑generering) |
| is_in_new_page | Hämtar eller anger ett bool‑värde som tvingar detta stycke att genereras på en ny sida.<br/>            Standard är false.(för pdf‑generering) |
| is_in_line_paragraph | Hämtar eller anger om ett stycke är inline.<br/>            Standard är false.(för pdf‑generering) |
| hyperlänk | Anger fragmentets hyperlänk. |
| z_index | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex <br/>            kommer att placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ <br/>            ZIndex kommer att placeras bakom texten på sidan. |
| replace_options | Hämtar alternativ för textersättning. Alternativen definierar beteendet när fragmenttext ersätts till kortare eller längre. |
| text | Hämtar eller anger strängtextobjektet som [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-objektet representerar. |
| text_state | Hämtar eller anger texttillståndet för den text som [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-objektet representerar. |
| segments | Hämtar textsegment för aktuell [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| position | Hämtar eller anger textposition för text som representeras med [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-objektet. |
| baseline_position | Hämtar textposition för text som representeras med [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-objektet.<br/>            YIndent-värdet i Position-strukturen representerar baslinjekoordinaten för textfragmentet. |
| rectangle | Hämtar rektangeln för TextFragment |
| sida | Hämtar sidan som innehåller TextFragment |
| formulär | Hämtar formulärobjektet som innehåller TextFragment |
| wrap_lines_count | Hämtar eller anger antal radbrytningar för detta stycke (endast för PDF-generering) |
| end_note | Hämtar eller anger styckets slutnot.(endast för PDF-generering) |
| foot_note | Hämtar eller anger styckets fotnot.(endast för PDF-generering) |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Klona fragmentet. |
| isolate_text_segments(start_index, length) | Hämtar [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) som representerar den specificerade delen av [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-texten. |
| clone_with_segments() | Klona fragmentet med alla segment. |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

