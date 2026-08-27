---
title: "PdfFileInfo"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att komma åt metadata i PDF‑dokument."
type: docs
weight: 270
url: /sv/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Representerar en klass för att komma åt metadata i PDF‑dokument.

Typen PdfFileInfo exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileInfo() | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo med standardvärden. |
| PdfFileInfo(input_stream) | Initierar en ny instans av klassen PdfFileInfo |
| PdfFileInfo(input_stream, password) | Initierar en ny instans av klassen PdfFileInfo |
| PdfFileInfo(input_file) | Initierar en ny instans av klassen PdfFileInfo |
| PdfFileInfo(input_file, password) | Initierar en ny instans av klassen PdfFileInfo |
| PdfFileInfo(document) | Initierar en ny instans av klassen PdfFileInfo |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| author | Hämtar eller anger författarinformationen för PDF-dokumentet. |
| is_encrypted | Kontrollerar om PDF-dokumentet är krypterat. |
| is_pdf_file | Kontrollerar om källinmatningen är en giltig PDF-fil. |
| use_strict_validation | Använder strikta valideringsregler via egenskapen [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Hämtar eller anger skapelsedatuminformationen för PDF-dokumentet. |
| creator | Hämtar eller anger skaparinformationen för PDF-dokumentet. |
| has_collection | Returnerar true om den aktuella inmatningsfilen är en 'Portfolio'-fil som innehåller en samling PDF-filer i den. |
| input_file | Hämtar eller anger inmatningsfilen. |
| input_stream | Hämtar eller anger inmatningsströmmen. |
| keywords | Hämtar eller anger nyckelordsinformationen för PDF-dokumentet. |
| mod_date | Hämtar eller anger ModDate-datinformationen för PDF-dokumentet. |
| number_of_pages | Hämtar antalet sidor i dokumentet. |
| producer | Hämtar producentinformationen för PDF-dokumentet. |
| subject | Hämtar eller anger ämnesinformationen för PDF-dokumentet. |
| titel | Hämtar eller anger titelinformationen för PDF-dokumentet. |
| password_type | Returnerar vilken typ av lösenord som skickades när PdfFileInfo-instansen skapades. Se möjliga värden i [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Observera att PDF-dokumentet kan öppnas med både användarlösenord (eller öppningslösenord) och ägarlösenord (eller behörighets‑/redigeringslösenord). |
| has_open_password | Returnerar true om ett lösenord krävs för att öppna ett lösenordsskyddat PDF-dokument. |
| has_edit_password | Returnerar true om ett lösenord krävs för att ändra behörigheter eller dokumentets säkerhetsegenskap.<br/>            Observera att denna egenskap endast kan läsas om ett giltigt lösenord angavs i konstruktorn för [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Om PasswordType är Inaccessible (vilket betyder att ett ogiltigt lösenord angavs) kommer läsning av denna egenskap att misslyckas med [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_doc) | Initierar fasaden. |
| bind_pdf(src_file) | Initierar fasaden. |
| bind_pdf(src_stream) | Initierar fasaden. |
| save(dest_stream) | Spara uppdaterat PDF-dokument i angiven ström. |
| save(dest_file) | Spara uppdaterat PDF-dokument i angiven fil. |
| save_new_info(output_stream) | Spara uppdaterat PDF-dokument i angiven ström. |
| save_new_info(output_file) | Spara uppdaterat PDF-dokument i angiven fil. |
| close() | Avinitierar instansen. |
| clear_info() | Rensar all metadata i PDF-dokumentet. |
| get_document_privilege() | Hämtar PDF-dokumentets privileginställningar. |
| get_meta_info(name) | Hämtar anpassad information för PDF-dokumentet med egenskapsnamnet. Om ingen egenskap matchar namnet returneras en tom sträng. |
| get_page_height(page_num) | Hämtar höjden på den angivna sidan. |
| get_page_rotation(page_num) | Hämtar rotationen för den angivna sidan. |
| get_page_width(page_num) | Hämtar bredden på den angivna sidan. |
| get_page_x_offset(page_num) | Hämtar den horisontella förskjutningen för den angivna sidans visningsområde. |
| get_page_y_offset(page_num) | Hämtar den vertikala förskjutningen för den angivna sidans visningsområde. |
| get_pdf_version() | Hämtar versionsinformationen för PDF-dokumentet. |
| set_meta_info(name, value) | Ställer in anpassad information för PDF-dokumentet. |
| save_new_info_with_xmp(output_file_name) | Ändrar de egenskaper som specificerats explicit genom att ställa in filinformation, andra egenskaper förblir. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

