---
title: "PdfViewer"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att visa eller skriva ut en PDF."
type: docs
weight: 370
url: /sv/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Representerar en klass för att visa eller skriva ut en PDF.

PdfViewer-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfViewer() | Initierar ett nytt [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) objekt. |
| PdfViewer(document) | Initierar en ny instans av PdfViewer-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| show_hidden_areas | Hämtar eller anger flagga som styr synligheten för dolda områden på sidan. |
| print_status | Hämtar resultatet av utskriftsjobbet. Om lyckat är null; annars ett undantagsobjekt. |
| use_intermidiate_image | Hämtar/anger användning av konvertering av pdf-sida till en mellanliggande png-fil under utskrift i filläge. Använd den när storleken på utdatafilen är viktig. |
| coordinate_type | Hämtar eller anger sidans koordinattyp (Media/Crop-boxar). CropBox-värdet används som standard. |
| print_as_image | Anger eller hämtar ett läge för PdfViewer att skriva ut som bild. |
| page_count | Hämtar sidantalet för den aktuella Pdf-filen. |
| password | Hämtar eller anger lösenord för inmatningsdokumentet. |
| print_page_dialog | Hämtar eller anger ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift. |
| print_as_grayscale | Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standardvärdet är falskt. |
| printer_job_name | Hämtar eller anger namn på dokumentet i skrivarkön när dokumentet skrivs ut. Standardvärdet är filnamnet. |
| form_presentation_mode | Hämtar eller anger formulärets presentationsläge. |
| rendering_options | Hämtar eller anger renderingsalternativ. |
| vertical_alignment | Hämtar eller anger ett värde som indikerar vertikal justering |
| horizontal_alignment | Hämtar eller anger ett värde som indikerar horisontell justering |
| auto_resize | Hämtar eller anger ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek. |
| auto_rotate | Hämtar eller anger ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation |
| auto_rotate_mode | Hämtar eller anger ett AutoRotateMode‑värde som indikerar rotationsriktning |
| resolution | Hämtar eller anger upplösning vid visning och utskrift. Högre upplösning ger långsammare hastighet. Standardvärdet är 150. |
| scale_factor | Hämtar eller anger ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1,0. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| print_large_pdf(file_path) | Öppnar och skriver ut en stor Pdf‑fil. Om din Pdf‑fil har hundratals sidor eller fler eller dess storlek är <br/>             mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| print_large_pdf(input_stream) | Öppnar och skriver ut en stor Pdf‑ström. Om din Pdf‑fil har hundratals sidor eller fler eller dess storlek är <br/>             mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| print_large_pdf(file_path, printer_settings) | Öppnar och skriver ut en stor Pdf‑fil med angivna skrivarinställningar. Om din Pdf‑fil har hundratals <br/>             sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| print_large_pdf(input_stream, printer_settings) | Öppnar och skriver ut en stor Pdf‑ström med angivna skrivarinställningar. Om din Pdf‑fil har hundratals <br/>             sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. |
| print_large_pdf(file_path, page_settings, printer_settings) | Öppnar och skriver ut en stor Pdf‑fil med angivna sidinställningar och skrivarinställningar. Om din Pdf <br/>             fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att <br/>             få bättre prestanda. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Öppnar och skriver ut en stor Pdf-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf <br/>             fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att <br/>             få bättre prestanda. |
| print_document_with_settings(page_settings, printer_settings) | Skriver ut Pdf-dokumentet med inställningar. Om dokumentets storlek inte är kompatibel med sidstorleken, kommer pdf.kit att utöka det för att passa sidstorleken. |
| print_document_with_settings(printer_settings) | Skriver ut Pdf-dokumentet med inställningar. Om dokumentets storlek inte är kompatibel med sidstorleken, kommer pdf.kit att utöka det för att passa sidstorleken. |
| open_pdf_file(file_path) | Öppnar en Pdf-fil, men avkodar inte faktiskt sidorna i Pdf-filen. |
| open_pdf_file(input_stream) | Öppnar en Pdf-filström. Men avkodar inte faktiskt sidorna i Pdf-filen. |
| bind_pdf(src_file) | Initierar fasaden. |
| bind_pdf(src_stream) | Initierar fasaden. |
| bind_pdf(src_doc) | Initierar fasaden. |
| save(dest_file) | Sparar det resulterande PDF-dokumentet till en fil. |
| save(dest_stream) | Sparar det resulterande PDF-dokumentet till en ström. |
| decode_all_pages() | Hämta sidorna i den aktuella pdf-filen. |
| decode_page(page_number) | Avkodar en sida i en Pdf-fil. |
| print_document_with_setup() | Skriver ut Pdf-dokumentet med en installationsdialog. Välj en skrivare med hjälp av dialogen. |
| print_document() | Skriver ut Pdf-dokumentet med en installationsdialog. Välj en skrivare med hjälp av dialogen. |
| get_default_page_settings() | Hämtar standard sidinställningar. |
| get_default_printer_settings() | Hämtar standard skrivarinställningar. |
| close_pdf_file() | Stänger den aktuella Pdf-filen. |
| close() | Stänger den aktuella Pdf-filen. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

