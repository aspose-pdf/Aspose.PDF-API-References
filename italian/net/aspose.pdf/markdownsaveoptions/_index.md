---
title: "Classe MarkdownSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.MarkdownSaveOptions class. Rappresenta la classe delle opzioni di salvataggio del documento nel formato markdown"
type: docs
weight: 7050
url: /it/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

Rappresenta la classe delle opzioni di salvataggio del documento nel formato markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Ottieni o imposta un'area Rectangle per estrarre il contenuto in markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Ottiene o imposta lo stile di enfasi per il documento generato. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Ottiene e imposta una proprietà che indica se i grafici vettoriali devono essere estratti. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Definisce i livelli di intestazione attesi da utilizzare nella strategia di riconoscimento delle intestazioni FontSize. Se il valore di questa proprietà è impostato, allora la strategia di riconoscimento delle intestazioni Heuristic verrà selezionata quando è impostato !:PdfToMarkdown.HeadingRecognitionStrategy.Auto, anche se il documento contiene segnalibri. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Ottiene o imposta la strategia di riconoscimento delle intestazioni. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Ottiene o imposta lo stile dell'intestazione per il documento generato. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Ottiene o imposta lo stile di interruzione di riga per il documento generato. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Ottiene e imposta il nome della directory in cui salvare le risorse del documento, come le immagini. Se il valore non è specificato, le immagini verranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory verrà creata automaticamente nella directory con il file markdown salvato. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Ottiene e imposta l'autorizzazione a convertire apice e pedice. Questo valore è vero per impostazione predefinita. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Ottiene e imposta l'autorizzazione all'uso del tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo avvolgerà l'immagine. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


