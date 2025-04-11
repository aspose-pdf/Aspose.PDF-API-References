---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfXmpMetadata. Classe per la manipolazione dei metadati XMP
type: docs
weight: 4640
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/
---
## Classe PdfXmpMetadata

Classe per la manipolazione dei metadati XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Costruttore per PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfXmpMetadata` basato sul *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Ottiene il conteggio degli elementi nella collezione. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Ottiene il dizionario dei campi di estensione. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Restituisce true se la collezione ha una dimensione fissa. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Restituisce true se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Restituisce true se la collezione è sincronizzata. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Ottiene o imposta il valore per chiave. (2 indicizzatori) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Ottiene le chiavi dal dizionario. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Ottiene l'oggetto di sincronizzazione della collezione. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Ottiene la collezione di valori nel dizionario. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Aggiunge un valore ai metadati XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Aggiunge un campo di estensione nei metadati. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Rimuove tutti gli elementi dall'oggetto. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Smaltisce Aspose.Pdf.Document legato a una facciata. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Controlla se il dizionario contiene la proprietà specificata. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Controlla se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Controlla se il dizionario contiene la chiave specificata. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Determina se questo dizionario contiene la chiave specificata. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Ottiene l'oggetto enumeratore del dizionario. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Ottiene l'URI del namespace per prefisso. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Ottiene il prefisso per URI del namespace. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Ottiene i metadati XmpMetadata del pdf di input in formato xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Ottiene una parte dei metadati XmpMetadata del pdf di input secondo un nome meta. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registra l'URI del namespace. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Rimuove l'elemento con la chiave specificata. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Rimuove la coppia chiave/valore dalla collezione. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Rimuove la chiave dal dizionario. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Tenta di trovare la chiave nel dizionario e recupera il valore se trovato. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* classe [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)