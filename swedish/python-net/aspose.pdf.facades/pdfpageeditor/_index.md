---
title: "PdfPageEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att redigera PDF-filens sida, inklusive rotera sidan, zooma sidan, flytta positionen och ändra sidstorlek."
type: docs
weight: 340
url: /sv/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Representerar en klass för att redigera PDF-filens sida, inklusive rotera sidan, zooma sidan, flytta positionen och ändra sidstorlek.

Typen PdfPageEditor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfPageEditor() | Konstruktor för klassen PdfPageEditor. |
| PdfPageEditor(document) | Initierar en ny instans av klassen PdfPageEditor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| transition_duration | Hämtar eller anger varaktigheten för övergångseffekten. |
| transition_type | Hämtar eller anger övergångsstil som ska användas när man går till den här sidan från en annan under en presentation. |
| display_duration | Hämtar eller anger visningstid för sidor. |
| process_pages | Hämtar eller anger sidnumren som ska redigeras. Som standard redigeras varje sida. |
| rotation | Hämtar eller anger rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270.<br/>            Standardvärdet är 0. |
| zoom | Hämtar eller anger zoomkoefficient. Värde 1.0 motsvarar 100%.<br/>            Standardvärdet är 1.0. |
| page_size | Hämtar eller anger sidstorleken för utdatafilen. |
| justering | Hämtar eller anger den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| horizontal_alignment | Hämtar eller anger den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| vertical_alignment | Hämtar eller anger den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Hämtar eller anger den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| SPLITVOUT | Vertikal delning ut |
| SPLITHOUT | Utgående horisontell delning |
| SPLITVIN | Ingående vertikal delning |
| SPLITHIN | IN Horisontell delning |
| BLINDV | Vertikala persienner |
| BLINDH | Vertikala persienner |
| INBOX | Inåtriktad låda |
| OUTBOX | Utåtriktad låda |
| LRWIPE | Vänster-höger svep |
| RLWIPE | Höger-vänster svep |
| BTWIPE | Botten-topp svep |
| TBWIPE | Topp-botten svep |
| UPPLÖS | Den gamla sidan upplöses |
| LRGLITTER | Vänster-höger glitter |
| TBGLITTER | Topp-botten glitter |
| DGLITTER | Diagonal glitter |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(output_file) | Sparar ändrat dokument i fil. |
| save(output_stream) | Sparar ändrat dokument i ström. |
| close() | Frigör alla resurser som är associerade med den aktuella fasaden. |
| move_position(move_x, move_y) | Flyttar ursprunget från (0, 0) till den angivna punkten. <br/>            Ursprunget är vänster-botten och enheten är punkt (1 tum = 72 punkter). |
| get_pages() | Returnerar totalt antal sidor. |
| get_page_size(page) | Returnerar sidstorleken för den angivna sidan. |
| get_page_rotation(page) | Returnerar rotationen för den angivna sidan. |
| get_page_box_size(page, page_box_name) | Returnerar storleken på den angivna rutan i dokumentet. |
| apply_changes() | Tillämpar ändringar som gjorts på dokumentets sidor. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

