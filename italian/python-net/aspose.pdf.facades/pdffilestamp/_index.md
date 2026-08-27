---
title: "PdfFileStamp"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe per aggiungere timbri (filigrana o sfondo) ai file PDF."
type: docs
weight: 320
url: /it/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Classe per aggiungere timbri (filigrana o sfondo) ai file PDF.

Il tipo PdfFileStamp espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp() | Costruttore di PdfFileStamp.<br/>            Il file di input e il file di output possono essere specificati tramite le proprietà corrispondenti. |
| PdfFileStamp(document) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp(document, output_file) | Inizializza una nuova istanza della classe PdfFileStamp |
| PdfFileStamp(document, output_stream) | Inizializza una nuova istanza della classe PdfFileStamp |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| optimize_size | Ottiene o imposta il flag di ottimizzazione. I flussi di risorse uguali nel file risultante vengono uniti in un unico oggetto PDF se questo flag è impostato. <br/>            Questo consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e requisiti di memoria maggiori.<br/>            Valore predefinito: false. |
| keep_security | Mantiene la sicurezza se vero. (Questa funzionalità sarà implementata nelle prossime versioni). |
| input_file | Ottiene o imposta il nome e il percorso del file di input. |
| input_stream | Ottiene o imposta il flusso di input. |
| output_file | Ottiene o imposta il nome e il percorso del file di output. |
| output_stream | Ottiene o imposta il flusso di output. |
| page_number_rotation | Ottiene o imposta la rotazione del numero di pagina. La rotazione è espressa in gradi. Il valore predefinito è 0. |
| page_height | Ottiene l'altezza della prima pagina nel file di origine. |
| page_width | Ottiene la larghezza della prima pagina nel file di input. |
| starting_number | Ottiene o imposta il numero iniziale per la prima pagina nel file di input. Le pagine successive saranno numerate a partire da questo valore. <br/>            Ad esempio, se StartingNumber è impostato a 100, le pagine del documento avranno i numeri 100, 101, 102... |
| numbering_style | Ottiene o imposta lo stile di numerazione della pagina. Valori possibili: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID del timbro del prossimo timbro aggiunto (inclusi intestazioni di pagina/piè di pagina/numeri di pagina). |
| POS_BOTTOM_MIDDLE | Posizione centrale inferiore. |
| POS_BOTTOM_RIGHT | Posizione in basso a destra. |
| POS_UPPER_RIGHT | Posizione in alto a destra. |
| POS_SIDES_RIGHT | Posizione a destra. |
| POS_UPPER_MIDDLE | Posizione centrale superiore. |
| POS_BOTTOM_LEFT | Posizione in basso a sinistra. |
| POS_SIDES_LEFT | Posizione a sinistra. |
| POS_UPPER_LEFT | Posizione in alto a sinistra. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il risultato nel file specificato. |
| save(dest_stream) | Salva il documento nello stream specificato. |
| add_page_number(format_string) | Aggiunge il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. <br/>            Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. |
| add_page_number(formatted_text) | Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che verrà sostituito con il numero di pagina.<br/>            Il numero di pagina è posizionato nella parte inferiore della pagina, centrato orizzontalmente. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Aggiunge il numero di pagina alle pagine del documento. |
| add_page_number(format_string, x, y) | Aggiunge il numero di pagina alle pagine del documento. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Aggiunge il numero di pagina alle pagine del documento. |
| add_page_number(formatted_text, x, y) | Aggiunge il numero di pagina alle pagine del documento. |
| add_page_number(format_string, position) | Aggiunge il numero di pagina alle pagine del documento. |
| add_page_number(formatted_text, position) | Aggiunge il numero di pagina alle pagine del documento. |
| add_header(formatted_text, top_margin) | Aggiunge l'intestazione alla pagina. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Aggiunge l'intestazione alla pagina. |
| add_header(image_file, top_margin) | Aggiunge l'immagine come intestazione alle pagine del file. |
| add_header(image_file, top_margin, left_margin, right_margin) | Aggiunge l'immagine come intestazione alle pagine del file. |
| add_header(image_stream, top_margin) | Aggiunge l'immagine come intestazione sulle pagine. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Aggiunge l'immagine come intestazione sulle pagine. |
| add_footer(formatted_text, bottom_margin) | Aggiunge il piè di pagina alle pagine del documento. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Aggiunge il piè di pagina alle pagine del documento. |
| add_footer(image_file, bottom_margin) | Aggiunge l'immagine come piè di pagina alle pagine del documento. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Aggiunge l'immagine come piè di pagina alle pagine del documento. |
| add_footer(image_stream, bottom_margin) | Aggiunge l'immagine come piè di pagina della pagina. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Aggiunge l'immagine come piè di pagina della pagina. |
| close() | Chiude i file aperti e salva le modifiche. <br/>            Attenzione. Se i flussi di input o output sono specificati non vengono chiusi dal metodo Close(). |
| add_stamp(stamp) | Aggiunge il timbro al file. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

