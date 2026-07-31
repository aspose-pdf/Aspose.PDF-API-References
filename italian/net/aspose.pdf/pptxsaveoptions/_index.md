---
title: "Classe PptxSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PptxSaveOptions. Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 9630
url: /it/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

Opzioni di salvataggio per l'esportazione in formato SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Questo gestore può essere utilizzato per gestire gli eventi di avanzamento della conversione, ad esempio può servire a mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate; un esempio di codice del gestore che mostra l'avanzamento sulla console è: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Attiva/disattiva il riconoscimento delle colonne di testo |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Se impostato su true, le immagini vengono separate da tutte le altre grafiche |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in un file PPT o PPTX

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// Il percorso al tuo file PPT o PPTX.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inizializza PptxSaveOptions
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Salva il file PPT o PPTX
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


