---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF."
type: docs
weight: 170
url: /it/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF.

Il tipo PdfAnnotationEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfAnnotationEditor() | Inizializza un nuovo oggetto [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | Inizializza una nuova istanza della classe PdfAnnotationEditor |
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
| import_annotations_from_xfdf(xfdf_file) | Importa tutte le annotazioni dal file XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Importa tutte le annotazioni dal flusso di dati XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Importa tutte le annotazioni dal file XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importa le annotazioni specificate dal file XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importa le annotazioni specificate dal flusso di dati XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Importa le annotazioni specificate dal flusso di dati XFDF. |
| import_annotations(annot_file, annot_type) | Importa le annotazioni specificate nel documento da un array di altri documenti PDF. |
| import_annotations(annot_file) | Importa le annotazioni specificate nel documento da un array di altri documenti PDF. |
| import_annotations(annot_file_stream, annot_type) | Importa le annotazioni specificate nel documento da un array di flussi di documenti PDF. |
| import_annotations(annot_file_stream) | Importa le annotazioni specificate nel documento da un array di flussi di documenti PDF. |
| flattening_annotations() | Appiattisce tutte le annotazioni nel documento. |
| flattening_annotations(flatten_settings) | Appiattisce tutte le annotazioni nel documento. |
| flattening_annotations(start, end, annot_type) | Appiattisce le annotazioni dei tipi specificati. |
| delete_annotations() | Elimina tutte le annotazioni nel documento. |
| delete_annotations(annot_type) | Elimina tutte le annotazioni del tipo specificato nel documento. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Esporta il contenuto dei tipi di annotazione specificati in XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Esporta il contenuto dei tipi di annotazione specificati in XFDF |
| extract_annotations(start, end, annot_types) | Restituisce l'elenco delle annotazioni dei tipi specificati. |
| extract_annotations(start, end, annot_types) | Restituisce l'elenco delle annotazioni dei tipi specificati. |
| close() | Rilascia tutte le risorse associate alla facciata corrente. |
| modify_annotations_author(start, end, src_author, des_author) | Modifica l'autore delle annotazioni nell'intervallo di pagine specificato. |
| delete_annotation(annot_name) | Elimina tutte le annotazioni del tipo specificato nel documento. |
| export_annotations_to_xfdf(xml_output_stream) | Esporta le annotazioni in uno stream. |
| modify_annotations(start, end, annotation) | Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato.<br/>            Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open. |
| redact_area(page_index, rect, color) | Oscura l'area nella pagina specificata. Tutti i contenuti vengono rimossi. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

