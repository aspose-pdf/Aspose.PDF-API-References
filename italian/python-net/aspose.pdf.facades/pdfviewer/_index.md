---
title: "PdfViewer"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per visualizzare o stampare un pdf."
type: docs
weight: 370
url: /it/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Rappresenta una classe per visualizzare o stampare un pdf.

Il tipo PdfViewer espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfViewer() | Inizializza un nuovo oggetto [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/). |
| PdfViewer(document) | Inizializza una nuova istanza della classe PdfViewer |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| show_hidden_areas | Ottiene o imposta il flag che controlla la visibilità delle aree nascoste nella pagina. |
| print_status | Ottiene il risultato del lavoro di stampa. Se ha avuto successo restituisce null; altrimenti, un oggetto eccezione. |
| use_intermidiate_image | Ottiene/imposta l'utilizzo della conversione della pagina pdf in un file png intermedio durante la stampa in modalità file. Usalo quando la dimensione del file di output è importante. |
| coordinate_type | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| print_as_image | Imposta o ottiene una modalità per PdfViewer di stampare come immagine. |
| page_count | Ottiene il conteggio delle pagine del file Pdf corrente. |
| password | Ottiene o imposta la password del documento di input. |
| print_page_dialog | Ottiene o imposta un valore booleano che indica se produrre la finestra di dialogo del numero di pagina durante la stampa. |
| print_as_grayscale | Ottiene o imposta un valore booleano che indica se la pagina viene stampata in scala di grigi. Per impostazione predefinita è false. |
| printer_job_name | Ottiene o imposta il nome del documento nella coda della stampante quando il documento viene stampato. Il valore predefinito è il nome del file. |
| form_presentation_mode | Ottiene o imposta la modalità di presentazione del modulo. |
| rendering_options | Ottiene o imposta le opzioni di rendering. |
| vertical_alignment | Ottiene o imposta un valore che indica l'allineamento verticale |
| horizontal_alignment | Ottiene o imposta un valore che indica l'allineamento orizzontale |
| auto_resize | Ottiene o imposta un valore bool che indica se il file deve essere stampato con dimensione ottimizzata. |
| auto_rotate | Ottiene o imposta un valore bool che indica se il file deve essere stampato con rotazione automatica |
| auto_rotate_mode | Ottiene o imposta un valore AutoRotateMode che indica la direzione di rotazione |
| resolution | Ottiene o imposta la risoluzione durante la visualizzazione e la stampa. Maggiore è la risoluzione, più lenta è la velocità. Il valore predefinito è 150. |
| scale_factor | Ottiene o imposta un valore a virgola mobile che indica il fattore di scala. Il valore predefinito è 1.0. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| print_large_pdf(file_path) | Apre e stampa un file Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è <br/>             più di 3 MB, questo metodo è consigliato per ottenere prestazioni migliori. |
| print_large_pdf(input_stream) | Apre e stampa un flusso Pdf di grandi dimensioni. Se il tuo file Pdf ha centinaia di pagine o più o la sua dimensione è <br/>             più di 3 MB, questo metodo è consigliato per ottenere prestazioni migliori. |
| print_large_pdf(file_path, printer_settings) | Apre e stampa un file Pdf di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia <br/>             di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori. |
| print_large_pdf(input_stream, printer_settings) | Apre e stampa un flusso Pdf di grandi dimensioni con le impostazioni della stampante specificate. Se il tuo file Pdf ha centinaia <br/>             di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per ottenere prestazioni migliori. |
| print_large_pdf(file_path, page_settings, printer_settings) | Apre e stampa un file Pdf di grandi dimensioni con le impostazioni di pagina e della stampante specificate. Se il tuo Pdf <br/>             ha centinaia di pagine o più o la sua dimensione è superiore a 3 MB, questo metodo è consigliato per <br/>             ottenere prestazioni migliori. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Apre e stampa un grande flusso Pdf con le impostazioni di pagina e di stampante specificate. Se il tuo file Pdf <br/>             ha centinaia di pagine o più o la sua dimensione supera i 3 MB, questo metodo è consigliato per <br/>             ottenere migliori prestazioni. |
| print_document_with_settings(page_settings, printer_settings) | Stampa il documento Pdf con le impostazioni. Se la dimensione del documento non è compatibile con la dimensione della pagina, pdf.kit lo estenderà per adattarlo alla dimensione della pagina. |
| print_document_with_settings(printer_settings) | Stampa il documento Pdf con le impostazioni. Se la dimensione del documento non è compatibile con la dimensione della pagina, pdf.kit lo estenderà per adattarlo alla dimensione della pagina. |
| open_pdf_file(file_path) | Apre un file Pdf, ma non decodifica effettivamente le pagine del file Pdf. |
| open_pdf_file(input_stream) | Apre un flusso di file Pdf. Ma non decodifica effettivamente le pagine del file Pdf. |
| bind_pdf(src_file) | Inizializza la facciata. |
| bind_pdf(src_stream) | Inizializza la facciata. |
| bind_pdf(src_doc) | Inizializza la facciata. |
| save(dest_file) | Salva il documento PDF risultante su file. |
| save(dest_stream) | Salva il documento PDF risultante su stream. |
| decode_all_pages() | Ottieni le pagine del file pdf corrente. |
| decode_page(page_number) | Decodifica una pagina di un file Pdf. |
| print_document_with_setup() | Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante usando la finestra di dialogo. |
| print_document() | Stampa il documento Pdf con una finestra di configurazione. Scegli una stampante usando la finestra di dialogo. |
| get_default_page_settings() | Ottiene le impostazioni di pagina predefinite. |
| get_default_printer_settings() | Ottiene le impostazioni della stampante predefinite. |
| close_pdf_file() | Chiude il file Pdf corrente. |
| close() | Chiude il file Pdf corrente. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

