---
title: PdfXmpMetadata
second_title: Aspose.PDF per .NET API Reference
description: Classe per la manipolazione con metadati XMP.
type: docs
weight: 2650
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Classe per la manipolazione con metadati XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | Costruttore per PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | Inizializza nuovo[`PdfXmpMetadata`](../pdfxmpmetadata) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | Ottiene il conteggio se gli elementi nella raccolta. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | Ottiene il dizionario dei campi di estensione. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | Restituisce true se la raccolta ha una dimensione fissa. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | Restituisce true se la raccolta è di sola lettura. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | Restituisce vero se la raccolta è sincronizzata. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | Ottiene o imposta il valore per chiave. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | Ottiene le chiavi dal dizionario. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | Ottiene l'oggetto di sincronizzazione della raccolta. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | Ottiene la raccolta di valori nel dizionario. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Aggiunge coppia con chiave e valore nel dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | Aggiunge valore ai metadati XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | Aggiunge il campo di estensione ai metadati. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | Rimuove tutti gli elementi dall'oggetto. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document rilegato con una facciata. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | Verifica se il dizionario contiene la proprietà specificata. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica che la coppia chiave-valore specificata sia contenuta nel dizionario. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | Verifica se il dizionario contiene la chiave specificata. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | Determina se questo dizionario contiene la chiave specificata. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | Ottiene l'oggetto enumeratore del dizionario. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | Ottiene l'URI dello spazio dei nomi per prefisso. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | Ottiene il prefisso dall'URI dello spazio dei nomi. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | Ottieni gli XmpMetadata del pdf di input in un formato xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | Ottieni una parte degli XmpMetadata del pdf di input secondo un meta name. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | Registra l'URI dello spazio dei nomi. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | Rimuove l'elemento con la chiave specificata. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Rimuove la coppia chiave/valore dalla raccolta. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | Rimuove la chiave dal dizionario. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Salva il documento PDF nel file specificato. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovato. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
