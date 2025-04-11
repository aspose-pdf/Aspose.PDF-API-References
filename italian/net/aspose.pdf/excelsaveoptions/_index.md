---
title: Class ExcelSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ExcelSaveOptions. Opzioni di salvataggio per l'esportazione in formato Excel
type: docs
weight: 4080
url: /it/net/aspose.pdf/excelsaveoptions/
---
## Classe ExcelSaveOptions

Opzioni di salvataggio per l'esportazione in formato Excel

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del carattere saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolivello OCR. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Formato di output |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Imposta su true se è necessario inserire una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è false; significa che la colonna vuota non sarà inserita. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Imposta su true se è necessario minimizzare il numero di fogli di lavoro nel workbook risultante. Il valore predefinito è false; significa che ogni pagina PDF sarà salvata come foglio di lavoro separato. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Imposta su true per utilizzare una divisione uniforme delle colonne attraverso il documento. Il valore predefinito è false; significa che la divisione delle colonne sarà indipendente per ogni pagina. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo sostanziale la conversione, quindi, si prega di utilizzare questa opzione solo quando è veramente necessario. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file XLS o XLSX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// The path to output xls or xlsx File.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ExcelSaveOptions	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Save xls or xlsx file
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### Vedi Anche

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)