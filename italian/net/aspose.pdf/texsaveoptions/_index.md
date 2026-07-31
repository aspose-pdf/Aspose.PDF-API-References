---
title: "Classe TeXSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.TeXSaveOptions. Opzioni di salvataggio per l'esportazione in formato TeX"
type: docs
weight: 10580
url: /it/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class

Opzioni di salvataggio per l'esportazione in formato TeX.

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Proprietà per il parametro _outDirectoryPath. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Restituisce il numero di pagine dopo la conversione. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | Aggiunge una codifica di carattere all'elenco delle codifiche dei caratteri |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | Cancella l'elenco delle codifiche dei caratteri |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file TeX

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// Il percorso del file TeX di output.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inizializza TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// Salva il file TeX
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


