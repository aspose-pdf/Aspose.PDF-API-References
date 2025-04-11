---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgSaveOptions. Opzioni di salvataggio per l'esportazione in formato SVG
type: docs
weight: 10230
url: /it/net/aspose.pdf/svgsaveoptions/
---
## Classe SvgSaveOptions

Opzioni di salvataggio per l'esportazione in formato SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da PDF ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolivello OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Specifica se l'output sarà creato come un'unica zip-archive. Si prega di fare riferimento al commento sulle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che si applicano anche al set compresso di file di output. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Questo campo può contenere la strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate creati (come BMP o JPEG incorporati) incorporati nel SVG salvato. Quella strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nel SVG generato. Se l'elaborazione per questo o quel file deve essere eseguita per qualche motivo dal codice del convertitore stesso, non nel codice personalizzato, si prega di impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non ci fosse alcun codice personalizzato esterno. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Specifica se scalare il documento di output da punti tipografici a pixel. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Questa opzione definisce se sarà creata una directory di destinazione (se non presente) con lo stesso nome del file di output richiesto invece del file di output richiesto stesso. In tal caso, quella directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima saranno creati esattamente nella directory richiesta come file di output principale, ma conterranno nel nome del file il suffisso _[2...n], definito dal numero di pagina, ad esempio, se si definisce il file di output "C:\AsposeTests\output.svg" e l'output conterrà diversi file svg di pagine, allora i file delle pagine saranno creati anche nella directory "C:\AsposeTests\" e avranno nomi 'output.svg', 'output_2.svg', 'output_3.svg', ecc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico identiche messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo significativo la conversione, quindi si prega di utilizzare questa opzione solo quando è davvero necessario. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Vedi Anche

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)