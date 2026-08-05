---
title: "PdfConverter"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF.<br/>            Contenuto supportato nei pdf: immagini, moduli, commenti."
type: docs
weight: 200
url: /it/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF.<br/>            Contenuto supportato nei pdf: immagini, moduli, commenti.

Il tipo PdfConverter espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfConverter() | Inizializza un nuovo oggetto [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | Inizializza una nuova istanza della classe PdfConverter |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| coordinate_type | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| show_hidden_areas | Ottiene o imposta il flag che controlla la visibilità delle aree nascoste nella pagina. |
| rendering_options | Ottiene o imposta le opzioni di rendering. |
| form_presentation_mode | Ottiene o imposta la modalità di presentazione del modulo. |
| resolution | Ottiene o imposta la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150. |
| start_page | Ottiene o imposta la posizione iniziale che si desidera convertire. Il valore minimo è 1. |
| end_page | Ottiene o imposta la posizione finale che si desidera convertire. |
| password | Ottiene o imposta la OwnerPassword del documento. |
| user_password | Ottiene o imposta la UserPassword del documento. |
| page_count | Ottiene il conteggio delle pagine. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(input_file) | Associa un file Pdf per la conversione. |
| bind_pdf(input_stream) | Associa uno Stream Pdf per la conversione. |
| bind_pdf(src_doc) | Inizializza la facciata. |
| save_as_tiff(output_file) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, compression_type) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, image_width, image_height) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, page_size) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, page_size, settings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| save_as_tiff(output_stream, compression_type) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_stream, page_size) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| save_as_tiff(output_stream, page_size, settings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico flusso TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| save_as_tiff(output_file, settings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_file, settings, converter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| save_as_tiff(output_stream, settings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico flusso TIFF. |
| save_as_tiff(output_stream, settings, converter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| save_as_tiff_class_f(output_stream, page_size) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| save_as_tiff_class_f(output_file) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| get_next_image(output_file) | Salva l'immagine su file con il formato immagine predefinito - jpeg. |
| get_next_image(output_file, page_size) | Salva l'immagine su file con la dimensione di pagina specificata e il formato immagine predefinito - jpeg. |
| get_next_image(output_file, format) | Salva l'immagine su file con il formato immagine fornito. |
| get_next_image(output_file, page_size, format) | Salva l'immagine su file con la dimensione di pagina e il formato immagine specificati. |
| get_next_image(output_stream) | Salva l'immagine nello stream con il formato immagine predefinito - jpeg. |
| get_next_image(output_stream, page_size) | Salva l'immagine nello stream con la dimensione di pagina specificata. |
| get_next_image(output_stream, format) | Salva l'immagine nello stream con il formato immagine specificato. |
| get_next_image(output_stream, page_size, format) | Salva l'immagine nello stream con la dimensione di pagina specificata. |
| get_next_image(output_file, format, image_width, image_height, quality) | Salva l'immagine su file con il formato immagine, le dimensioni e la qualità specificati. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| get_next_image(output_file, format, image_width, image_height, quality) | Salva l'immagine su file con il formato immagine, la dimensione dell'immagine e la qualità specificati. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Salva l'immagine nello stream con il formato immagine, la dimensione e la qualità specificati. |
| get_next_image(output_file, format, image_width, image_height) | Salva l'immagine su file con il formato immagine, le dimensioni e la qualità specificati. |
| get_next_image(output_stream, format, image_width, image_height) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| get_next_image(output_stream, format, quality) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| get_next_image(output_stream, page_size, format, quality) | Salva l'immagine nello stream con la dimensione di pagina, il formato immagine e la qualità specificati. |
| get_next_image(output_file, format, quality) | Salva l'immagine su file con il formato immagine, le dimensioni e la qualità specificati. |
| get_next_image(output_file, page_size, format, quality) | Salva l'immagine su file con la dimensione di pagina, il formato immagine e la qualità specificati. |
| close() | Chiudi l'istanza di PdfConverter e rilascia le risorse. |
| do_convert() | Esegui alcune operazioni iniziali per convertire un documento pdf in immagini. |
| has_next_image() | Indica se il file pdf ha più immagini o meno. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Nessuno |
| merge_images_as_tiff(input_images_streams) | Unisce l'elenco di flussi tiff in un unico flusso tiff a più fotogrammi. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

