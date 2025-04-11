---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions class. Save options for export to Doc format
type: docs
weight: 3750
url: /it/net/aspose.pdf/docsaveoptions/
---
## Classe DocSaveOptions

Opzioni di salvataggio per l'esportazione in formato Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Usa interruzioni di paragrafo o di riga |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione in batch è applicabile alla coppia di formati sorgente e di destinazione. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Ottiene o imposta la conversione per i font Type3. Nei font Type 3, i glifi devono essere definiti da flussi di operatori grafici. Questo significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolivello OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Formato di output |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Risoluzione X delle immagini convertite. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Risoluzione Y delle immagini convertite. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Questo parametro è utilizzato per raggruppare le righe di testo in paragrafi. Determina quanto possono essere distanti due righe di testo relative. Specificato in centinaia di percento dell'altezza delle righe di testo. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità di salvataggio in memoria. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Modalità di riconoscimento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Attiva il riconoscimento dei punti elenco |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Nei PDF, le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte dobbiamo rilevare gruppi di caratteri indipendenti che sono in realtà parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che devono essere trattati come distanza tra le parole durante il riconoscimento delle parole nel PDF sorgente. (la presenza di uno spazio vuoto di almeno questa larghezza tra le lettere significa che gli elementi testuali appartengono a parole diverse). È normalizzato alla dimensione del font - 1.0 significa 100% della dimensione del font presunto della parola. ATTENZIONE! È utilizzato solo nei casi in cui il PDF sorgente contiene font specifici raramente usati per i quali il valore ottimale non può essere calcolato dal font. Quindi, nella stragrande maggioranza dei casi, questo parametro non cambia nulla nel documento risultante. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Ottiene o imposta la procedura per il salvataggio dei font. Se impostato su true, ricarichiamo i font su ogni pagina per evitare l'influenza delle proprietà dei font precedenti e caricare il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Questo gestore può essere utilizzato per gestire eventi di progresso della conversione, ad esempio può essere utilizzato per mostrare una barra di progresso o messaggi sulla quantità attuale di pagine elaborate, un esempio di codice del gestore che mostra il progresso sulla console è: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, prova a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi, per favore, utilizza questa opzione solo quando è davvero necessario. |

### Esempi

Il seguente esempio mostra come convertire un file PDF in un file DOC o DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Vedi Anche

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interfaccia [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)