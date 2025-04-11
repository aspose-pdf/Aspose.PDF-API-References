---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.MarkdownSaveOptions. Rappresenta la classe delle opzioni di salvataggio del documento nel formato markdown
type: docs
weight: 6910
url: /it/net/aspose.pdf/markdownsaveoptions/
---
## Classe MarkdownSaveOptions

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
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Ottiene o imposta un'area rettangolare da estrarre nel markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Ottiene o imposta lo stile di enfasi per il documento generato. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolivello OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Ottiene e imposta una proprietà che indica se le grafiche vettoriali devono essere estratte. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Definisce i livelli di intestazione previsti da utilizzare nella strategia di riconoscimento degli header FontSize. Se il valore di questa proprietà è impostato, allora la strategia di riconoscimento degli header !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic sarà selezionata quando le strategie !:PdfToMarkdown.HeadingRecognitionStrategy.Auto sono impostate anche se il documento contiene segnalibri. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Ottiene o imposta la strategia di riconoscimento degli heading. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Ottiene o imposta lo stile dell'intestazione per il documento generato. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Ottiene o imposta lo stile di interruzione di linea per il documento generato. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Ottiene e imposta il nome della directory per salvare le risorse del documento come immagini. Se il valore non è specificato, le immagini saranno scritte nella stessa directory del file markdown stesso. Questo non è un percorso, è solo un nome! Questa directory sarà creata automaticamente nella directory con il file markdown salvato. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Ottiene e imposta il permesso di convertire apici e pedici. Questo valore è true per impostazione predefinita. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Ottiene e imposta il permesso di utilizzare un tag img per inserire immagini a sinistra e a destra del testo. In questo caso, nel visualizzatore markdown, il testo si avvolgerà attorno all'immagine. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo significativo la conversione, quindi, si prega di utilizzare questa opzione solo quando è davvero necessario. |

### Vedi anche

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)