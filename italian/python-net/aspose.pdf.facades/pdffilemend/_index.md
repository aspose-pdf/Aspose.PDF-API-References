---
title: "PdfFileMend"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente."
type: docs
weight: 280
url: /it/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente.

Il tipo PdfFileMend espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileMend() | Costruttore. |
| PdfFileMend(input_file_name, output_file_name) | Inizializza una nuova istanza della classe PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Inizializza una nuova istanza della classe PdfFileMend |
| PdfFileMend(document) | Inizializza una nuova istanza della classe PdfFileMend |
| PdfFileMend(document, output_file_name) | Inizializza una nuova istanza della classe PdfFileMend |
| PdfFileMend(document, dest_stream) | Inizializza una nuova istanza della classe PdfFileMend |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| input_stream | Imposta lo stream di input. |
| output_stream | Imposta lo stream di output. |
| input_file | Imposta il file di input. |
| output_file | Imposta il file di output. |
| wrap_mode | Imposta o ottiene l'algoritmo di word wrapping. Vedi WordWrapMode e IsWordWrap. |
| text_positioning_mode | Imposta o ottiene la strategia di posizionamento del testo. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            La modalità predefinita è Legacy. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il documento PDF nel file specificato. |
| save(dest_stream) | Salva il documento PDF nello stream specificato. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Aggiunge l'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Aggiunge l'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Non implementato. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Non implementato. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Non implementato. |
| close() | Chiude l'oggetto PdfFileMend. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

