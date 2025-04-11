---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions class. Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere utilizzata come parametro del metodo OptimizeResources
type: docs
weight: 7980
url: /it/net/aspose.pdf.optimization/optimizationoptions/
---
## Classe OptimizationOptions

Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere utilizzata come parametro del metodo OptimizeResources().

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
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Se vero, i contenuti delle pagine verranno riutilizzati quando il documento è ottimizzato per pagine uguali. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Se questo flag è impostato su `true`, gli oggetti Pdf verranno impacchettati in Objest Streams e compressi per ridurre la dimensione del file pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Codifica dell'immagine che verrà utilizzata. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Se questo flag è impostato su vero, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se i contenuti del flusso sono uguali), allora questi flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre la dimensione del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Livello di scansione. Scansioni più profonde (valore più alto) richiedono più tempo ma possono produrre file di risultato più piccoli. Valore predefinito: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione superiore, verrà ridimensionata. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Rimuovi informazioni private (informazioni sui pezzi di pagina). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Se questo flag è impostato su vero, tutti gli oggetti del documento verranno controllati e gli oggetti non utilizzati (cioè oggetti che non hanno alcun riferimento) verranno rimossi dal documento. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Se questo flag è impostato su vero, ogni risorsa viene controllata per il suo utilizzo. Se la risorsa non viene mai utilizzata, allora la risorsa viene rimossa. Questo può ridurre la dimensione del documento, ad esempio quando le pagine sono state estratte dal documento. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | I caratteri verranno convertiti in sottoinsiemi se impostati su vero. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Rendi i caratteri non incorporati se impostati su vero. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Crea una strategia di ottimizzazione con tutte le opzioni attivate. Si prega di notare che sono attivate solo le opzioni che non modificano alcuna funzionalità del documento. Cioè, la compressione delle immagini e l'unembedding dei caratteri non saranno abilitate (e possono essere incorporate manualmente). |

### Vedi Anche

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)