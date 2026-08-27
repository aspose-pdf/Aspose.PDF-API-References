---
title: "Classe DocSaveOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.DocSaveOptions. Opzioni di salvataggio per l'esportazione in formato Doc"
type: docs
weight: 3870
url: /it/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

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
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati sorgente e destinazione. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi dei caratteri saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione PDF in altri formati ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Ottiene o imposta la conversione per i font Type3. Nei font Type3, i glifi devono essere definiti da flussi di operatori grafici. Ciò significa che nell'output DOC/DOCX vediamo immagini invece di testo. Imposta questo flag su true per convertire i font Type3 in TTF e ottenere testo nel file risultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità di estrazione di immagini o testo per i documenti PDF con sottolivello OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Formato di output |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Risoluzione X delle immagini convertite. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Risoluzione Y delle immagini convertite. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Questo parametro è usato per raggruppare le linee di testo in paragrafi. Determina quanto distanti possono essere due linee di testo relative. Specificato in centinaia di percentuale dell'altezza delle linee di testo. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Definisce il percorso (nome file o nome directory) per contenere i dati temporanei durante la conversione in modalità salvataggio in memoria. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Modalità di riconoscimento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Attiva il riconoscimento dei punti elenco |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | In Pdf le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte è necessario individuare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere trattata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine. (la presenza di uno spazio vuoto almeno di questa larghezza tra le lettere indica che gli elementi testuali appartengono a parole diverse). È normalizzata alla dimensione del carattere – 1,0 significa il 100 % della dimensione del carattere della parola presunta. ATTENTION!Viene utilizzata solo nei casi in cui il PDF di origine contiene font specifici raramente usati per i quali il valore ottimale non può essere calcolato dal font. Pertanto, nella stragrande maggioranza dei casi questo parametro non cambia nulla nel documento risultante. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Ottiene o imposta la procedura per il risalvataggio dei font. Se impostato su true, ricarichiamo i font in ogni pagina per evitare l'influenza delle proprietà dei font precedenti e carichiamo il font appena creato da zero. Imposta questa opzione su false se desideri migliorare le prestazioni. Il valore predefinito è true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. Continuare è l'azione predefinita e l'operazione di salvataggio prosegue, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di salvataggio deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Questo gestore può essere utilizzato per gestire gli eventi di avanzamento della conversione, ad esempio può servire a mostrare una barra di avanzamento o messaggi sul numero corrente di pagine elaborate; un esempio di codice del gestore che mostra l'avanzamento sulla console è: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in pochi thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria. |

### Esempi

Il seguente esempio mostra come convertire un file PDF in un file DOC o DOCX

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// Il percorso per il file DOC o DOCX di output.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Imposta la modalità di riconoscimento su Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Imposta la prossimità orizzontale a 2,5
			RelativeHorizontalProximity = 2.5f,
			// Abilita il valore per riconoscere i punti elenco durante il processo di conversione
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

### Vedi anche

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


