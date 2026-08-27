---
title: "PdfFileEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Implementerar operationer för PDF‑filkonkatenering, delning, extrahering av sidor, skapande av häfte osv."
type: docs
weight: 220
url: /sv/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc.

Typen PdfFileEditor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileEditor() | Initierar en ny instans av klassen PdfFileEditor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| conversion_log | Hämtar logg för konverteringsprocessen. |
| merge_duplicate_layers | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om den här egenskapen är sann. <br/>            Annars kommer lager med samma namn att sparas som olika lager i det resulterande dokumentet. |
| copy_outlines | Om sant kopieras konturerna. |
| copy_logical_structure | Om sant kopieras filens logiska struktur när sammanslagning utförs. |
| merge_duplicate_outlines | Om true, duplicerade konturer slås ihop. |
| preserve_user_rights | Om true, tillämpas användarrättigheterna för det första dokumentet på det sammanslagna dokumentet. Användarrättigheterna för alla andra dokument ignoreras. |
| incremental_updates | Om true, görs inkrementella uppdateringar under sammanslagning. |
| optimize_size | Hämtar eller anger optimeringsflagga. Likadana resursströmmar i den resulterande filen slås samman till ett PDF-objekt om detta flagga är satt. <br/>            Detta möjliggör att minska den resulterande filstorleken men kan orsaka långsammare körning och högre minneskrav.<br/>            Standardvärde: false. |
| corrupted_items | Array av påträffade problem när sammanslagning utfördes. För varje korrupt dokument som skickas till Concatenate() <br/>            skapas en ny CorruptedItem‑post.<br/>            Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Denna egenskap definierar beteendet när sammanslagningsprocessen stöter på en korrupt fil.<br/>            Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| owner_password | Anger ägarens lösenord om den ursprungliga Pdf‑filen är krypterad.<br/>            Denna egenskap är ännu inte implementerad. |
| allow_concatenate_exceptions | Om satt till true kastas undantag om ett fel inträffar. Annars kastas inga undantag och metoderna returnerar false vid misslyckande. |
| close_concatenated_streams | Om satt till true stängs strömmarna efter operationen. |
| unique_suffix | Formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär slås ihop.<br/>            Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror.<br/>            Till exempel, om UniqueSuffix = \"ABC%NUM%\" blir fältnamnen för \"fieldName\":<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 osv. |
| keep_actions | Om true kopieras åtgärder från källdokumenten. Standardvärde : true. |
| keep_fields_unique | Om true görs fältnamnen unika när formulär slås ihop.<br/>            Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix. |
| remove_signatures | Om true tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| use_disk_buffer | Om detta alternativ används kommer destinationsdokumentet att sparas på disk periodiskt och ytterligare sammanslagning kommer att tillämpas på det som inkrementella uppdateringar. |
| concatenation_packet_size | Antal dokument som sammanslogs innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Sammanfogar två filer. |
| try_concatenate(src, dest) | Sammanfogar dokument. |
| try_concatenate(input_files, output_file) | Sammanfogar filer till en fil. |
| try_concatenate(input_stream, output_stream) | Sammanfogar filer |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Sammanfogar två filer. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Sammanfogar filer |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Lägger till sidor som väljs från en array av dokument i portStreams.<br/>            Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Lägger till sidor som väljs från portFiles-dokument. <br/>            Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Infogar sidor från en annan fil i inmatnings‑Pdf‑filen. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Infogar sidor från en annan fil i inmatnings‑Pdf‑filen. |
| try_delete(input_file, page_number, output_file) | Tar bort sidor som specificerats av ett nummerarray från inmatningsfilen, sparas som en ny Pdf‑fil. |
| try_delete(input_stream, page_number, output_stream) | Tar bort sidor som specificerats av ett nummerarray från inmatningsfilen, sparas som en ny Pdf‑fil. |
| try_extract(input_file, start_page, end_page, output_file) | Extraherar sidor från inmatningsfilen, sparas som en ny Pdf‑fil. |
| try_extract(input_file, page_number, output_file) | Extraherar sidor som anges av en talarray, sparar som en ny PDF‑fil. |
| try_extract(input_stream, page_number, output_stream) | Extraherar sidor som anges av en talarray, sparar som en ny Pdf‑fil. |
| try_split_from_first(input_file, location, output_file) | Delar Pdf-filen från första sidan till den angivna platsen och sparar den främre delen som en ny fil. |
| try_split_from_first(input_stream, location, output_stream) | Delar från början till den angivna platsen och sparar den främre delen i output Stream. |
| try_split_to_end(input_file, location, output_file) | Delar från platsen, och sparar den bakre delen som en ny fil. |
| try_split_to_end(input_stream, location, output_stream) | Delar från den angivna platsen, och sparar den bakre delen som en ny file Stream. |
| try_make_booklet(input_file, output_file) | Skapar häfte från indatafilen till utdatafilen. |
| try_make_booklet(input_stream, output_stream) | Skapar häfte från InputStream till outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Skapar häfte från inputFile till outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Skapar häfte från input stream och sparar resultatet i output stream. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Skapar anpassat häfte från firstInputFile till outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Skapar anpassat häfte från firstInputStream till outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Skapar anpassat häfte från firstInputFile till outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Skapar häfte från firstInputStream till outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Skapar N-Up-dokument från den första inmatningsströmmen till output stream. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| try_make_n_up(input_files, output_file, is_sidewise) | Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile. <br/>            Varje sida i outputFile kommer att innehålla flera sidor, som är en kombination av sidor <br/>            i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt <br/>            om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream.<br/>            Varje sida i outputStream kommer att innehålla flera sidor, som är en kombination av sidor <br/>            i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt <br/>            om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Skapar N-Up-dokument från inmatningsfilen till outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Ändrar storlek på innehållet i dokumentets sidor. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Ändrar storlek på innehållet i dokumentets sidor. <br/>            Krymper innehållet på sidan och lägger till marginaler.<br/>            Ny storlek på innehållet anges i standardenhetsmått. |
| try_resize_contents(source, destination, pages, parameters) | Ändrar storlek på innehållet i dokumentets sidor. Om sidan krymps läggs tomma marginaler till runt sidan. |
| concatenate(first_input_file, sec_input_file, output_file) | Kedjar ihop filer och sparar reslt i HttpResposnse-objektet. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Kedjar ihop filer och lagrar resultatet i HttpResponse-objektet. |
| concatenate(src, dest) | Sammanfogar dokument. |
| concatenate(input_files, output_file) | Kedjar ihop filer och sparar reslt i HttpResposnse-objektet. |
| concatenate(input_stream, output_stream) | Kedjar ihop filer och lagrar resultatet i HttpResponse-objektet. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Kedjar ihop filer och sparar reslt i HttpResposnse-objektet. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Kedjar ihop filer och lagrar resultatet i HttpResponse-objektet. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Lägger till dokument i källdokumentet och sparar resultatet i svarobjektet. |
| append(input_file, port_files, start_page, end_page, output_file) | Lägger till dokument i källdokumentet och sparar resultatet i HttpResponse-objektet. |
| append(input_file, port_file, start_page, end_page, output_file) | Lägger till dokument i källdokumentet och sparar resultatet i HttpResponse-objektet. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Lägger till dokument i källdokumentet och sparar resultatet i svarobjektet. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Infogar dokument i ett annat dokument och lagrar resultatet i svarobjektet. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Infogar dokument i ett annat dokument och lagrar resultatet i svarobjektet. |
| delete(input_file, page_number, output_file) | Raderar angivna sidor från dokumentet och lagrar resultatet i HttpResponse-objektet. |
| delete(input_stream, page_number, output_stream) | Raderar angivna sidor från dokumentet och sparar resultatet i HttpResponse-objektet. |
| extract(input_file, start_page, end_page, output_file) | Extraherar angivna sidor från källfilen och lagrar resultatet i HttpResponse-objektet. |
| extract(input_file, page_number, output_file) | Extraherar angivna sidor från källfilen och lagrar resultatet i HttpResponse-objektet. |
| extract(input_stream, start_page, end_page, output_stream) | Extraherar angivna sidor från källfilen och lagrar resultatet i ett HttpResponse-objekt. |
| extract(input_stream, page_number, output_stream) | Extraherar angivna sidor från källfilen och lagrar resultatet i ett HttpResponse-objekt. |
| split_from_first(input_file, location, output_file) | Delar dokumentet från första sidan till platsen och sparar resultatet i HttpResponse-objekt. |
| split_from_first(input_stream, location, output_stream) | Delar dokumentet från början till angiven plats och lagrar resultatet i ett HttpResponse-objekt. |
| split_to_end(input_file, location, output_file) | Delar från angiven plats och sparar den bakre delen i ett HttpResponse-objekt. |
| split_to_end(input_stream, location, output_stream) | Delar från angiven plats och sparar den bakre delen i ett HttpResponse-objekt. |
| make_booklet(input_file, output_file) | Skapar häfte från källfilen och lagrar resultatet i HttpResponse-objekt. |
| make_booklet(input_stream, output_stream) | Skapa häfte från PDF-fil och lagra det i HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Skapar häfte från källfilen och lagrar resultatet i HttpResponse-objekt. |
| make_booklet(input_stream, output_stream, page_size) | Skapa häfte från PDF-fil och lagra det i HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Skapar häfte från källfilen och lagrar resultatet i HttpResponse-objekt. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Skapa häfte från PDF-fil och lagra det i HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Skapar häfte från källfilen och lagrar resultatet i HttpResponse-objekt. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Skapa häfte från PDF-fil och lagra det i HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| make_n_up(input_stream, output_stream, x, y) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| make_n_up(first_input_file, second_input_file, output_file) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| make_n_up(input_files, output_file, is_sidewise) | Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile. <br/>            Varje sida i outputFile kommer att innehålla flera sidor, som är en kombination av sidor <br/>            i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt <br/>            om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| make_n_up(input_streams, output_stream, is_sidewise) | Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream.<br/>            Varje sida i outputStream kommer att innehålla flera sidor, som är en kombination av sidor <br/>            i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt <br/>            om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| make_n_up(input_file, output_file, x, y, page_size) | Skapar N-up-dokument och lagrar resultatet i ett HttpResponse-objekt. |
| split_to_pages(input_file, file_name_template) | Delar upp PDF-filen i enkelsidiga dokument. |
| split_to_pages(input_stream, file_name_template) | Dela PDF-filen i enkelsidiga dokument och spara den i angiven sökväg. Sökvägen är specificerad av fältnamnsmallen. |
| resize_contents(source, destination, pages, parameters) | Ändrar storlek på innehållet i sidor i dokumentet. Om en sida har krympts läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| resize_contents(source, destination, pages, new_width, new_height) | Ändrar storlek på innehållet i dokumentets sidor. <br/>            Krymper innehållet på sidan och lägger till marginaler.<br/>            Ny storlek på innehållet anges i standardenhetsmått. |
| resize_contents(source, destination, pages, new_width, new_height) | Ändrar storlek på innehållet i dokumentets sidor. <br/>            Krymper innehållet på sidan och lägger till marginaler.<br/>            Ny storlek på innehållet anges i standardenhetsmått. |
| resize_contents(source, destination, pages, parameters) | Ändrar storlek på innehållet i sidor i dokumentet. Om en sida har krympts läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| resize_contents(source, pages, parameters) | Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan. |
| resize_contents(source, parameters) | Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ändrar storlek på innehållet i dokumentets sidor.<br/>            Krymper innehållet på sidan och lägger till marginaler.<br/>            Ny storlek på innehållet anges i procent. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ändrar storlek på innehållet i dokumentets sidor.<br/>            Krymper innehållet på sidan och lägger till marginaler.<br/>            Ny storlek på innehållet anges i procent. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändrar storlek på sidinnehållet och lägger till specificerade marginaler. <br/>            Marginalerna anges i standardenhetsmått. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändrar storlek på sidinnehållet och lägger till specificerade marginaler. <br/>            Marginalerna anges i standardenhetsmått. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändrar storlek på sidinnehållet och lägger till specificerade marginaler.<br/>            Marginalerna anges i procent av den ursprungliga sidstorleken. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändrar storlek på sidinnehållet och lägger till specificerade marginaler.<br/>            Marginalerna anges i procent av den ursprungliga sidstorleken. |
| add_page_break(src, dest, page_breaks) | Lägger till sidbrytningar i dokumentets sidor. |
| add_page_break(src, dest, page_breaks) | Lägger till sidbrytningar i dokumentets sidor. |
| add_page_break(src, dest, page_breaks) | Lägger till sidbrytningar i dokumentets sidor. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

