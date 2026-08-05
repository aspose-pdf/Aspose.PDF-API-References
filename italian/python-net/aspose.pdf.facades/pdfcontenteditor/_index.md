---
title: "PdfContentEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per modificare il contenuto dei file PDF."
type: docs
weight: 190
url: /it/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Rappresenta una classe per modificare il contenuto dei file PDF.

Il tipo PdfContentEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfContentEditor() | Il costruttore dell'oggetto PdfContentEditor. |
| PdfContentEditor(document) | Inizializza una nuova istanza della classe PdfContentEditor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| text_search_options | Ottiene o imposta le opzioni di ricerca del testo. |
| text_edit_options | Ottiene o imposta le opzioni di modifica del testo. |
| text_replace_options | Ottiene o imposta le opzioni di sostituzione del testo. |
| replace_text_strategy | Un insieme di parametri per l'operazione di sostituzione del testo |
| DOCUMENT_OPEN | Tipo di evento documento. Apre un documento. |
| DOCUMENT_CLOSE | Tipo di evento documento. Chiude un documento. |
| DOCUMENT_WILL_SAVE | Tipo di evento documento. Esegue un'azione prima del salvataggio. |
| DOCUMENT_SAVED | Tipo di evento documento. Esegue un'azione dopo il salvataggio. |
| DOCUMENT_WILL_PRINT | Tipo di evento documento. Esegue un'azione prima della stampa. |
| DOCUMENT_PRINTED | Un tipo di evento del documento. Esegui un'azione dopo la stampa. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(input_file) | Associa un file PDF per la modifica. |
| bind_pdf(input_stream) | Associa un flusso PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il documento PDF nel file specificato. |
| save(dest_stream) | Salva il documento PDF nello stream specificato. |
| create_web_link(rect, url, original_page, clr) | Crea un collegamento web nel documento PDF. |
| create_web_link(rect, url, original_page) | Crea un collegamento web nel documento PDF. |
| create_local_link(rect, des_page, original_page, clr) | Crea un collegamento locale nel documento PDF. |
| create_local_link(rect, des_page, original_page) | Crea un collegamento locale nel documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Crea un collegamento a un'altra pagina di documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Crea un collegamento a un'altra pagina di documento PDF. |
| create_application_link(rect, application, page, clr) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| create_application_link(rect, application, page) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | Crea un'annotazione di allegato file. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Crea un'annotazione di allegato file. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Crea un'annotazione di allegato file. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Crea un'annotazione di allegato file. |
| add_document_attachment(file_attachment_path, description) | Aggiunge un allegato al documento senza annotazione. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Aggiunge un allegato al documento senza annotazione. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Crea un'annotazione di timbro di gomma. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Crea un'annotazione di timbro di gomma. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Crea un'annotazione di timbro di gomma. |
| delete_image(page_number, index) | Elimina le immagini specificate nella pagina specificata. |
| delete_image() | Elimina le immagini specificate nella pagina specificata. |
| replace_text(src_string, the_page, dest_string, text_state) | Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo da sostituire. |
| replace_text(src_string, dest_string) | Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo da sostituire. |
| replace_text(src_string, the_page, dest_string) | Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo da sostituire. |
| replace_text(src_string, dest_string, text_state) | Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo da sostituire. |
| replace_text(src_string, dest_string, font_size) | Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo da sostituire. |
| delete_stamp_by_ids(stamp_ids) | Elimina i timbri con ID specificati da tutte le pagine del documento. |
| delete_stamp_by_ids(page_number, stamp_ids) | Elimina i timbri con ID specificati da tutte le pagine del documento. |
| delete_stamp_by_id(page_number, stamp_id) | Elimina i timbri con ID specificati da tutte le pagine del documento. |
| delete_stamp_by_id(stamp_id) | Elimina i timbri con ID specificati da tutte le pagine del documento. |
| close() | Chiude il documento aperto. |
| extract_link() | Estrae la collezione di istanze Link contenute nel documento PDF. |
| create_java_script_link(code, rect, original_page, color) | Crea un collegamento a JavaScript nel documento PDF. |
| create_text(rect, title, contents, open, icon, page) | Crea un'annotazione di testo nel documento PDF |
| create_free_text(rect, contents, page) | Crea un'annotazione di testo libero nel documento PDF |
| create_markup(rect, contents, type, page, clr) | Crea un'annotazione di markup nel documento PDF. |
| create_popup(rect, contents, open, page) | Crea un'annotazione popup nel documento PDF. |
| delete_attachments() | Elimina tutti gli allegati nel documento PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Crea un'annotazione di linea. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Crea un'annotazione quadrato-circolare. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Crea un'annotazione curva. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Crea un'annotazione poligonale. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Crea un'annotazione polilinea. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Crea un'annotazione caret. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Crea un segnalibro con l'azione specificata. |
| add_document_additional_action(event_type, code) | Aggiunge un'azione aggiuntiva per l'evento del documento. |
| remove_document_open_action() | Rimuove l'azione di apertura dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano un'azione 'GoTo' esplicita all'avvio. |
| change_viewer_preference(viewer_attribution) | Modifica la preferenza di visualizzazione. |
| get_viewer_preference() | Restituisce la preferenza di visualizzazione. |
| replace_image(page_number, index, image_file) | Sostituisce l'immagine specificata nella pagina indicata del documento PDF con un'altra immagine. |
| create_movie(rect, file_path, page) | Crea annotazioni video. |
| create_sound(rect, file_path, name, page, rate) | Crea annotazioni audio. |
| delete_stamp(page_number, index) | Elimina più timbri nella pagina specificata per indice dei timbri. |
| hide_stamp_by_id(page_number, stamp_id) | Nasconde il timbro. Dopo la nasconditura, la visibilità del timbro può essere ripristinata con il metodo ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Mostra il timbro che è stato nascosto da HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Cambia la posizione del timbro nella pagina. |
| move_stamp(page_number, stamp_index, x, y) | Cambia la posizione del timbro nella pagina. |
| get_stamps(page_number) | Restituisce un array di timbri nella pagina. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

