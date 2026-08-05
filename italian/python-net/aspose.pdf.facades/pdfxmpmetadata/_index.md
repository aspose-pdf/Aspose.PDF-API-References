---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe per la manipolazione dei metadati XMP."
type: docs
weight: 380
url: /it/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Classe per la manipolazione dei metadati XMP.

Il tipo PdfXmpMetadata espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfXmpMetadata() | Costruttore per PdfXmpMetadata. |
| PdfXmpMetadata(document) | Inizializza una nuova istanza della classe PdfXmpMetadata |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| chiavi | Ottiene le chiavi dal dizionario. |
| valori | Ottiene la collezione di valori nel dizionario. |
| is_fixed_size | Restituisce true se la collezione ha dimensione fissa. |
| is_synchronized | Restituisce true se la collezione è sincronizzata. |
| sync_root | Ottiene l'oggetto di sincronizzazione della collezione. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il documento PDF nel file specificato. |
| save(dest_stream) | Salva il documento PDF nello stream specificato. |
| add(key, value) | Aggiunge valore ai metadati XMP. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Aggiunge campo di estensione nei metadati. |
| add(key, value) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| add(key, value) | Aggiunge campo di estensione nei metadati. |
| remove(key) | Rimuove l'elemento con la chiave specificata. |
| remove(key) | Rimuove la chiave dal dizionario. |
| contains(key) | Verifica se il dizionario contiene la chiave specificata. |
| contains(property) | Verifica se il dizionario contiene la proprietà specificata. |
| get_xmp_metadata() | Ottieni lo XmpMetadata del PDF di input in formato XML. |
| get_xmp_metadata(name) | Ottieni una parte dei XmpMetadata del PDF di input in base a un nome meta. |
| close() | Rilascia tutte le risorse associate alla facciata corrente. |
| register_namespace_uri(prefix, namespace_uri) | Registra l'URI dello spazio dei nomi. |
| get_namespace_uri_by_prefix(prefix) | Ottiene l'URI dello spazio dei nomi per prefisso. |
| get_prefix_by_namespace_uri(namespace_uri) | Ottiene il prefisso per l'URI dello spazio dei nomi. |
| contains_key(key) | Determina se questo dizionario contiene la chiave specificata. |
| try_get_value(key, value) | Prova a trovare la chiave nel dizionario e recupera il valore se trovata. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

