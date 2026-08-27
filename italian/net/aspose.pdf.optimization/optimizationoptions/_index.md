---
title: "Classe OptimizationOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Optimization.OptimizationOptions classe. Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources"
type: docs
weight: 8120
url: /it/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources().

```csharp
public class OptimizationOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Se true il contenuto della pagina verrà riutilizzato quando il documento viene ottimizzato per pagine uguali. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Se questo flag è impostato su `true`, gli oggetti Pdf verranno inseriti in Objest Streams e compressi per ridurre la dimensione del file pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Codifica immagine che verrà utilizzata. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Se questo flag è impostato su true, Resource streams verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), allora questi flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre la dimensione del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta, verrà ridimensionata. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Rimuove le informazioni private (informazioni sulla porzione di pagina). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Se questo flag è impostato su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) saranno rimossi dal documento. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Se questo flag è impostato su true, ogni risorsa viene controllata per il suo utilizzo. Se una risorsa non è mai usata, allora la risorsa viene rimossa. Questo può ridurre la dimensione del documento, ad esempio quando le pagine sono state estratte dal documento. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | I caratteri verranno convertiti in sottoinsiemi se impostati su true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Rendi i caratteri non incorporati se impostati su true. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Crea una strategia di ottimizzazione con tutte le opzioni attivate. Si prega di notare che vengono attivate solo le opzioni che non modificano alcuna funzionalità del documento. Ad esempio, la compressione delle immagini e la rimozione dell'incorporamento dei caratteri non saranno abilitate (e possono essere incorporate manualmente). |

### Vedi anche

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


