---
title: "PdfFileSanitization"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta l'API di sanificazione e recupero.<br/>            Usala se non riesci a creare/aprire documenti in altro modo."
type: docs
weight: 290
url: /it/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Rappresenta l'API di sanificazione e recupero.<br/>            Usala se non riesci a creare/aprire documenti in altro modo.

Il tipo PdfFileSanitization espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileSanitization() | Inizializza una nuova istanza della classe PdfFileSanitization |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| log | Dopo che il file è stato salvato, puoi verificare cosa è stato fatto con il file. |
| use_trim_top | Consente di rimuovere i dati prima dei dati pdf. |
| use_trim_bottom | Consente di rimuovere i dati dopo i dati pdf |
| use_rebuild_xref_and_trailer | Consente di generare un nuovo xref e trailer per il documento. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(input_file) | Associa un file Pdf per la sanificazione. |
| bind_pdf(input_stream) | Associa uno stream Pdf per la sanificazione. |
| bind_pdf(src_doc) | Inizializza la facciata. |
| save(output_file) | Salva il PDF risultante su file. |
| save(output_stream) | Salva il PDF risultante su stream. |
| close() | Chiude la facciata. |
| recover() | Recupera il documento.<br/>            Usa le proprietà per personalizzare. |
| trim_top() | Rimuove i dati prima di %PDF. |
| trim_bottom() | Rimuove i dati dopo l'ultimo %%EOF. |
| rebuild_xref_and_trailer() | Rimuove il vecchio xref con trailer e crea un nuovo xref con trailer. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

