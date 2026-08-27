---
title: "PdfFileEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Implementa operazioni con la concatenazione di file PDF, divisione, estrazione di pagine, creazione di opuscoli, ecc."
type: docs
weight: 220
url: /it/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc.

Il tipo PdfFileEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileEditor() | Inizializza una nuova istanza della classe PdfFileEditor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| conversion_log | Ottiene il registro del processo di conversione. |
| merge_duplicate_layers | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. <br/>            Altrimenti, i livelli con nomi uguali saranno salvati come livelli diversi nel documento risultante. |
| copy_outlines | Se true, gli outline verranno copiati. |
| copy_logical_structure | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| merge_duplicate_outlines | Se true, gli outline duplicati vengono uniti. |
| preserve_user_rights | Se true, i diritti utente del primo documento vengono applicati al documento concatenato. I diritti utente di tutti gli altri documenti vengono ignorati. |
| incremental_updates | Se true, vengono effettuati aggiornamenti incrementali durante la concatenazione. |
| optimize_size | Ottiene o imposta il flag di ottimizzazione. I flussi di risorse uguali nel file risultante vengono uniti in un unico oggetto PDF se questo flag è impostato. <br/>            Questo consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e requisiti di memoria maggiori.<br/>            Valore predefinito: false. |
| corrupted_items | Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato a Concatenate() <br/>            viene creata una nuova voce CorruptedItem.<br/>            Questa proprietà può essere usata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto.<br/>            I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted. |
| owner_password | Imposta la password del proprietario se il file Pdf di input sorgente è crittografato.<br/>            Questa proprietà non è ancora implementata. |
| allow_concatenate_exceptions | Se impostato su true, vengono generate eccezioni se si verifica un errore. Altrimenti le eccezioni non vengono generate e i metodi restituiscono false in caso di fallimento. |
| close_concatenated_streams | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| unique_suffix | Formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli vengono concatenati.<br/>            Questa stringa deve contenere la sottostringa %NUM% che verrà sostituita con numeri.<br/>            Ad esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc. |
| keep_actions | Se true le azioni verranno copiate dai documenti sorgente. Valore predefinito: true. |
| keep_fields_unique | Se true i nomi dei campi verranno resi unici quando i moduli sono concatenati.<br/>            I suffissi verranno aggiunti ai nomi dei campi, il modello di suffisso può essere specificato nella proprietà UniqueSuffix. |
| remove_signatures | Se true, tutte le firme verranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| use_disk_buffer | Se questa opzione è usata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali. |
| concatenation_packet_size | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Concatena due file. |
| try_concatenate(src, dest) | Concatena documenti. |
| try_concatenate(input_files, output_file) | Concatena file in un unico file. |
| try_concatenate(input_stream, output_stream) | Concatena file |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena due file. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena file |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Aggiunge pagine, scelte dall'array di documenti in portStreams.<br/>            Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Aggiunge pagine, scelte dai documenti portFiles. <br/>            Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Inserisce pagine da un altro file nel file Pdf di input. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Inserisce pagine da un altro file nel file Pdf di input. |
| try_delete(input_file, page_number, output_file) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. |
| try_delete(input_stream, page_number, output_stream) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. |
| try_extract(input_file, start_page, end_page, output_file) | Estrae pagine dal file di input, le salva come un nuovo file Pdf. |
| try_extract(input_file, page_number, output_file) | Estrae pagine specificate da un array di numeri, le salva come un nuovo file PDF. |
| try_extract(input_stream, page_number, output_stream) | Estrae pagine specificate da un array di numeri, le salva come un nuovo file Pdf. |
| try_split_from_first(input_file, location, output_file) | Divide il file Pdf dalla prima pagina fino alla posizione specificata, e salva la parte anteriore come un nuovo file. |
| try_split_from_first(input_stream, location, output_stream) | Divide dall'inizio fino alla posizione specificata, e salva la parte anteriore nello Stream di output. |
| try_split_to_end(input_file, location, output_file) | Divide dalla posizione, e salva la parte posteriore come un nuovo file. |
| try_split_to_end(input_stream, location, output_stream) | Divide dalla posizione specificata e salva la parte finale come un nuovo file Stream. |
| try_make_booklet(input_file, output_file) | Crea un opuscolo dal file di input al file di output. |
| try_make_booklet(input_stream, output_stream) | Crea un opuscolo dallo InputStream all'outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Crea un opuscolo dall'inputFile all'outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Crea un opuscolo dal flusso di input e salva il risultato nel flusso di output. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Crea un opuscolo personalizzato dal firstInputFile all'outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Crea un opuscolo personalizzato dal firstInputStream all'outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crea un opuscolo personalizzato dal firstInputFile all'outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Crea un opuscolo dal firstInputStream all'outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Crea un documento N-Up dal firstInputFile all'outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Crea un documento N-Up dal flusso di input e salva il risultato nel flusso di output. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Crea un documento N-Up dal primo flusso di input al flusso di output. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Crea un documento N-Up dal firstInputFile all'outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Crea un documento N-Up dal flusso di input e salva il risultato nel flusso di output. |
| try_make_n_up(input_files, output_file, is_sidewise) | Crea un documento N-Up dai file PDF di input multipli verso outputFile. <br/> Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Crea un documento N-Up dai flussi PDF di input multipli verso outputStream.<br/> Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Crea un documento N-Up dal file di input verso outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Ridimensiona il contenuto delle pagine del documento. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Ridimensiona il contenuto delle pagine del documento. <br/> Riduce il contenuto della pagina e aggiunge margini.<br/> La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. |
| try_resize_contents(source, destination, pages, parameters) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina. |
| concatenate(first_input_file, sec_input_file, output_file) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Concatena i file e memorizza il risultato nell'oggetto HttpResponse. |
| concatenate(src, dest) | Concatena documenti. |
| concatenate(input_files, output_file) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| concatenate(input_stream, output_stream) | Concatena i file e memorizza il risultato nell'oggetto HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena i file e memorizza il risultato nell'oggetto HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto response. |
| append(input_file, port_files, start_page, end_page, output_file) | Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Aggiunge documenti al documento sorgente e salva il risultato nell'oggetto response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto response. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto response. |
| delete(input_file, page_number, output_file) | Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpResponse. |
| delete(input_stream, page_number, output_stream) | Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| extract(input_file, page_number, output_file) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| extract(input_stream, page_number, output_stream) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| split_from_first(input_file, location, output_file) | Divide il documento dalla prima pagina fino alla posizione e salva il risultato negli oggetti HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Divide il documento dall'inizio fino alla posizione specificata e memorizza il risultato nell'oggetto HttpResponse. |
| split_to_end(input_file, location, output_file) | Divide a partire dalla posizione specificata e salva la parte finale nell'oggetto HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Divide a partire dalla posizione specificata e salva la parte finale nell'oggetto HttpResponse. |
| make_booklet(input_file, output_file) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpResponse. |
| make_booklet(input_stream, output_stream) | Crea un opuscolo dal file PDF e lo memorizza in HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Crea un opuscolo dal file PDF e lo memorizza in HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Crea un opuscolo dal file PDF e lo memorizza in HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Crea un opuscolo dal file PDF e lo memorizza in HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Crea un documento N-Up dai file PDF di input multipli verso outputFile. <br/> Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| make_n_up(input_streams, output_stream, is_sidewise) | Crea un documento N-Up dai flussi PDF di input multipli verso outputStream.<br/> Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| make_n_up(input_file, output_file, x, y, page_size) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| split_to_pages(input_file, file_name_template) | Divide il file PDF in documenti a pagina singola. |
| split_to_pages(input_stream, file_name_template) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. Il percorso è specificato dal modello di nome campo. |
| resize_contents(source, destination, pages, parameters) | Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina. Il risultato è memorizzato nell'oggetto HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Ridimensiona il contenuto delle pagine del documento. <br/> Riduce il contenuto della pagina e aggiunge margini.<br/> La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. |
| resize_contents(source, destination, pages, new_width, new_height) | Ridimensiona il contenuto delle pagine del documento. <br/> Riduce il contenuto della pagina e aggiunge margini.<br/> La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. |
| resize_contents(source, destination, pages, parameters) | Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina. Il risultato è memorizzato nell'oggetto HttpResponse. |
| resize_contents(source, pages, parameters) | Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta. |
| resize_contents(source, parameters) | Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ridimensiona il contenuto delle pagine del documento.<br/>            Riduce il contenuto della pagina e aggiunge i margini.<br/>            La nuova dimensione del contenuto è specificata in percentuale. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ridimensiona il contenuto delle pagine del documento.<br/>            Riduce il contenuto della pagina e aggiunge i margini.<br/>            La nuova dimensione del contenuto è specificata in percentuale. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. <br/>            I margini sono specificati nelle unità di spazio predefinite. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. <br/>            I margini sono specificati nelle unità di spazio predefinite. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati.<br/>            I margini sono specificati in percentuale della dimensione iniziale della pagina. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati.<br/>            I margini sono specificati in percentuale della dimensione iniziale della pagina. |
| add_page_break(src, dest, page_breaks) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| add_page_break(src, dest, page_breaks) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| add_page_break(src, dest, page_breaks) | Aggiunge interruzioni di pagina nelle pagine del documento. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

