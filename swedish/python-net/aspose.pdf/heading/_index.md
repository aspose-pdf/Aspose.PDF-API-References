---
title: "Rubrik"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar rubrik."
type: docs
weight: 460
url: /sv/python-net/aspose.pdf/heading/
---

## Heading class

Representerar rubrik.

Rubrik-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Heading(level) | Initierar en ny instans av Rubrik-klassen |
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
| toc_page | Hämtar sidan som innehåller denna rubrik. |
| top | Hämtar det övre Y‑värdet för denna rubrik. |
| start_number | Hämtar rubrikens startnummer. |
| is_auto_sequence | Hämtar om rubriken ska numreras automatiskt. |
| is_in_list | Hämtar om rubriken ska finnas i innehållsförteckningslistan. |
| destination_page | Hämtar destinationssidan. |
| level | Hämtar nivån. |
| style | Hämtar eller anger stil. |
| user_label | Hämtar eller anger användaretikett. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Klona rubriken. |
| isolate_text_segments(start_index, length) | Hämtar [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) som representerar den specificerade delen av [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-texten. |
| clone_with_segments() | Klona rubriken med alla segment. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

