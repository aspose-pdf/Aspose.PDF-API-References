---
title: "PdfExtractor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe per estrarre immagini e testo da un documento PDF."
type: docs
weight: 210
url: /it/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Classe per estrarre immagini e testo da un documento PDF.

Il tipo PdfExtractor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfExtractor() | Inizializza un nuovo oggetto [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/). |
| PdfExtractor(document) | Inizializza una nuova istanza della classe PdfExtractor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| start_page | Ottiene o imposta la pagina iniziale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| end_page | Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| extract_text_mode | Imposta la modalità per il risultato dell'estrazione del testo. |
| text_search_options | Ottiene o imposta le opzioni di ricerca del testo. |
| extract_image_mode | Imposta la modalità per il processo di estrazione delle immagini. |
| is_bidi | È vero quando il testo contiene simboli ebraici o arabi. Questo caso deve essere considerato particolarmente perché<br/>            le funzioni di stringa cambiano il loro comportamento e avviano l'elaborazione del testo da destra a sinistra (eccetto i numeri <br/>            e altri caratteri non testuali). |
| resolution | Imposta o ottiene la risoluzione per le immagini estratte.<br/>            Il valore predefinito è 150.<br/>            Le immagini con una risoluzione maggiore sono più nitide.<br/>            Tuttavia aumentare il valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini.<br/>            Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300. |
| password | Ottiene o imposta la password del file di input. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(input_file) | Associa il file PDF di input. |
| bind_pdf(input_stream) | Associa il documento PDF dallo stream. |
| bind_pdf(src_doc) | Inizializza la facciata. |
| extract_text() | Estrae il testo da un documento PDF utilizzando la codifica Unicode. |
| extract_text(encoding) | Estrae il testo da un documento PDF utilizzando la codifica specificata. |
| get_text(output_file) | Salva il testo su file. vedi anche:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Salva il testo su stream. vedi anche:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Salva il testo su stream. vedi anche:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo. |
| get_next_image(output_file, format) | Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo. |
| get_next_image(output_stream, format) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato. |
| get_next_image(output_stream) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato. |
| extract_attachment() | Estrae gli allegati da un documento PDF. |
| extract_attachment(attachment_file_name) | Estrae l'allegato nel file PDF per nome dell'allegato. |
| get_next_page_text(output_file) | Salva il testo di una pagina su file. |
| get_next_page_text(output_stream) | Salva il testo di una pagina su stream. |
| close() | Rilascia l'Aspose.Pdf.Document associato a una facciata. |
| extract_image() | Estrai le immagini dal file PDF. |
| has_next_image() | Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. |
| get_attach_names() | Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima dell'uso di questo metodo. |
| get_attachment(output_path) | Salva l'allegato su file. |
| has_next_page_text() | Indica se è possibile ottenere più testi o meno. |
| get_attachment_info() | Ottiene l'elenco degli allegati. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

