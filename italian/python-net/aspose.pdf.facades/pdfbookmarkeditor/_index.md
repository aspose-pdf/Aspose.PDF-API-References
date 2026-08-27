---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per gestire i segnalibri dei file PDF, includendo creazione, modifica, esportazione, importazione e cancellazione."
type: docs
weight: 180
url: /it/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Rappresenta una classe per gestire i segnalibri dei file PDF, includendo creazione, modifica, esportazione, importazione e cancellazione.

Il tipo PdfBookmarkEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfBookmarkEditor() | Inizializza un nuovo oggetto [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/). |
| PdfBookmarkEditor(document) | Inizializza una nuova istanza della classe PdfBookmarkEditor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il documento PDF nel file specificato. |
| save(dest_stream) | Salva il documento PDF nello stream specificato. |
| create_bookmarks() | Crea segnalibri per tutte le pagine. |
| create_bookmarks(bookmark) | Crea segnalibri per tutte le pagine. |
| create_bookmarks(color, bold_flag, italic_flag) | Crea segnalibri per tutte le pagine con il colore e lo stile specificati (grassetto, corsivo). |
| create_bookmark_of_page(bookmark_name, page_number) | Crea un segnalibro per la pagina specificata. |
| create_bookmark_of_page(bookmark_name, page_number) | Crea segnalibri per le pagine specificate. |
| delete_bookmarks() | Elimina tutti i segnalibri del documento PDF. |
| delete_bookmarks(title) | Elimina il segnalibro del documento PDF. |
| extract_bookmarks() | Estrae i segnalibri di tutti i livelli dal documento. |
| extract_bookmarks(upper_level) | Estrae i segnalibri di tutti i livelli dal documento. |
| extract_bookmarks(title) | Estrae i segnalibri con il titolo specificato. |
| extract_bookmarks(bookmark) | Estrae i segnalibri di tutti i livelli dal documento. |
| export_bookmarks_to_xml(xml_file) | Esporta i segnalibri in un file XML. |
| export_bookmarks_to_xml(stream) | Esporta i segnalibri in uno stream XML. |
| import_bookmarks_with_xml(xml_file) | Importa i segnalibri nel documento da un file XML. |
| import_bookmarks_with_xml(stream) | Importa i segnalibri nel documento da un file XML. |
| close() | Rilascia tutte le risorse associate alla facciata corrente. |
| modify_bookmarks(s_title, d_title) | Modifica il titolo del segnalibro in base al titolo specificato. |
| extract_bookmarks_to_html(pdf_file, css_file) | Esporta i segnalibri in un file HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Esporta i segnalibri in un file HTML. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

