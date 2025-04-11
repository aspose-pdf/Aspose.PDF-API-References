---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions class. Contains options for loading/importing EPUB file into pdf document
type: docs
weight: 4050
url: /it/net/aspose.pdf/epubloadoptions/
---
## Classe EpubLoadOptions

Contiene opzioni per il caricamento/importazione di un file EPUB in un documento pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Crea opzioni di caricamento predefinite per convertire un file EPUB in un documento pdf. Dimensione della pagina pdf predefinita - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Crea opzioni di caricamento con dimensione della pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Ottiene o imposta il Css personalizzato da applicare durante l'apertura del documento Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Di default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Ottiene un riferimento all'oggetto che rappresenta le informazioni sui margini. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Ottiene o imposta la dimensione della pagina di output per l'importazione. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENZIONE! La funzionalità è implementata ma non è ancora stata inserita nell'API pubblica poiché è emerso un problema bloccante nel layer OSHARED per un documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.), di solito hanno un design fluttuante, quindi, consentono di adattare la dimensione della pagina richiesta. Ma a volte il contenuto ha posizioni orizzontali specificate o dimensioni che non consentono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa dovrebbe essere fatto in questo caso (cioè quando la dimensione del contenuto non si adatta alla dimensione della pagina iniziale richiesta del documento PDF risultante). |

## Esempi

Il seguente esempio mostra come convertire un file EPUB in un file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)