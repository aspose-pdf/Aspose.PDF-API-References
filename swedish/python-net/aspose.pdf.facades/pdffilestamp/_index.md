---
title: "PdfFileStamp"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer."
type: docs
weight: 320
url: /sv/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer.

PdfFileStamp-typen visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp(input_stream, output_stream) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp(input_file, output_file, keep_security) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp(input_stream, output_stream, keep_security) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp() | Konstruktor för PdfFileStamp.<br/>            Indatafil och utdatafil kan specificeras via motsvarande egenskaper. |
| PdfFileStamp(document) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp(document, output_file) | Initierar en ny instans av PdfFileStamp-klassen |
| PdfFileStamp(document, output_stream) | Initierar en ny instans av PdfFileStamp-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| optimize_size | Hämtar eller anger optimeringsflagga. Likadana resursströmmar i den resulterande filen slås samman till ett PDF-objekt om detta flagga är satt. <br/>            Detta möjliggör att minska den resulterande filstorleken men kan orsaka långsammare körning och högre minneskrav.<br/>            Standardvärde: false. |
| keep_security | Behåller säkerheten om true. (Denna funktion kommer att implementeras i kommande versioner). |
| input_file | Hämtar eller anger namn och sökväg för indatafil. |
| input_stream | Hämtar eller anger indataflöde. |
| output_file | Hämtar eller anger namn och sökväg för utdatafil. |
| output_stream | Hämtar eller anger utdataflöde. |
| page_number_rotation | Hämtar eller anger rotation för sidnummer. Rotation är i grader. Standard är 0. |
| page_height | Hämtar höjden på den första sidan i källfilen. |
| page_width | Hämtar bredden på den första sidan i indatafilen. |
| starting_number | Hämtar eller anger startnummer för den första sidan i indatafilen. Efterföljande sidor kommer att numreras med början från detta värde. <br/>            Till exempel om StartingNumber är satt till 100, kommer dokumentets sidor att ha nummer 100, 101, 102... |
| numbering_style | Hämtar eller anger sidnumreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | Stämpel-ID för nästa tillagda stämpel (inkluderande sidhuvuden/ sidfot/ sidnummer). |
| POS_BOTTOM_MIDDLE | Nedre mittposition. |
| POS_BOTTOM_RIGHT | Position längst ner till höger. |
| POS_UPPER_RIGHT | Övre högra position. |
| POS_SIDES_RIGHT | Höger position. |
| POS_UPPER_MIDDLE | Övre mittposition. |
| POS_BOTTOM_LEFT | Position längst ner till vänster. |
| POS_SIDES_LEFT | Vänster position. |
| POS_UPPER_LEFT | Övre vänstra positionen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar resultatet i angiven fil. |
| save(dest_stream) | Sparar dokumentet till angiven ström. |
| add_page_number(format_string) | Lägg till sidnummer i filen. Sidnumreringstexten kan innehålla #‑tecken som kommer att ersättas med sidans nummer. <br/>            Sidnumret placeras i botten av sidan centrerat horisontellt. |
| add_page_number(formatted_text) | Lägger till sidnummer på sidan. Sidnumret kan innehålla #‑tecken som kommer att ersättas med sidnumret.<br/>            Sidnumret placeras i botten av sidan centrerat horisontellt. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Lägger till sidnummer på dokumentets sidor. |
| add_page_number(format_string, x, y) | Lägger till sidnummer på dokumentets sidor. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Lägger till sidnummer på dokumentets sidor. |
| add_page_number(formatted_text, x, y) | Lägger till sidnummer på dokumentets sidor. |
| add_page_number(format_string, position) | Lägger till sidnummer på dokumentets sidor. |
| add_page_number(formatted_text, position) | Lägger till sidnummer på dokumentets sidor. |
| add_header(formatted_text, top_margin) | Lägger till sidhuvud på sidan. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Lägger till sidhuvud på sidan. |
| add_header(image_file, top_margin) | Lägger till bild som sidhuvud på filens sidor. |
| add_header(image_file, top_margin, left_margin, right_margin) | Lägger till bild som sidhuvud på filens sidor. |
| add_header(image_stream, top_margin) | Lägger till bild som sidhuvud på sidorna. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Lägger till bild som sidhuvud på sidorna. |
| add_footer(formatted_text, bottom_margin) | Lägger till sidfot på dokumentets sidor. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Lägger till sidfot på dokumentets sidor. |
| add_footer(image_file, bottom_margin) | Lägger till bild som sidfot på dokumentets sidor. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Lägger till bild som sidfot på dokumentets sidor. |
| add_footer(image_stream, bottom_margin) | Lägger till bild som sidfot på sidan. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Lägger till bild som sidfot på sidan. |
| close() | Stänger öppna filer och sparar ändringar. <br/>            Varning. Om in- eller utdataflöden är angivna stängs de inte av Close()-metoden. |
| add_stamp(stamp) | Lägger till stämpel i filen. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

