---
title: "PdfFileMend"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF‑dokument."
type: docs
weight: 280
url: /sv/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF‑dokument.

Typen PdfFileMend visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileMend() | Konstruktor. |
| PdfFileMend(input_file_name, output_file_name) | Initierar en ny instans av klassen PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Initierar en ny instans av klassen PdfFileMend |
| PdfFileMend(document) | Initierar en ny instans av klassen PdfFileMend |
| PdfFileMend(document, output_file_name) | Initierar en ny instans av klassen PdfFileMend |
| PdfFileMend(document, dest_stream) | Initierar en ny instans av klassen PdfFileMend |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| input_stream | Ställer in inmatningsströmmen. |
| output_stream | Ställer in utmatningsströmmen. |
| input_file | Ställer in inmatningsfilen. |
| output_file | Ställer in utmatningsfilen. |
| wrap_mode | Ställer in eller hämtar algoritmen för radbrytning. Se WordWrapMode och IsWordWrap. |
| text_positioning_mode | Ställer in eller hämtar strategin för textpositionering. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Standardläget är Legacy. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Ej implementerad. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ej implementerad. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ej implementerad. |
| close() | Stänger PdfFileMend-objektet. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

