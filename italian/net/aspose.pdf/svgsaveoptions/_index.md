---
title: "Classe SvgSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.SvgSaveOptions. Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 10410
url: /it/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Specifica se l'output verrà creato come un unico archivio zip. Si prega di fare riferimento al commento delle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file immagine esterni referenziati creati (come BMP o JPEG incorporati) incorporati nello SVG salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nello SVG generato. Se l'elaborazione di questo o di quell'altro file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti dal convertitore stesso come se non esistesse alcun codice personalizzato esterno. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Specifica se scalare il documento di output da punti tipografici a pixel. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Questa opzione definisce se creare una directory di destinazione (se ancora assente) con lo stesso nome del file di output richiesto invece del file di output stesso. In tal caso, la directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta come file di output principale, ma con un suffisso nel nome file _[2...n], definito dal numero di pagina, ad es. se si definisce il file di output "C:\AsposeTests\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine saranno creati anche nella directory "C:\AsposeTests\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file SVG

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// Il percorso al file SVG di output.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inizializza SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Salva file SVG
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

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


