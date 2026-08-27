---
title: "Classe EpubLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.EpubLoadOptions class. Contiene le opzioni per il caricamento/importazione di file EPUB in un documento pdf."
type: docs
weight: 4170
url: /it/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Contiene opzioni per il caricamento/importazione del file EPUB in un documento pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Crea le opzioni di caricamento predefinite per la conversione di file EPUB in un documento pdf. Dimensione pagina pdf predefinita - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Crea le opzioni di caricamento con la dimensione pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Ottiene o imposta il Css personalizzato da applicare all'apertura del documento Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Ottiene un riferimento all'oggetto che rappresenta le informazioni di margine. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Ottiene o imposta la dimensione della pagina di output per l'importazione. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento delle istruzioni (se presenti) del CSS del documento importato relative all'uso dei margini. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel livello OSHARED riscontrato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia a volte il contenuto ha posizioni orizzontali o dimensioni specificate che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del PDF di risultato). |

## Esempi

Il seguente esempio mostra come convertire un file EPUB in un file PDF.

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il percorso del tuo file EPUB.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Inizializza EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Salva file PDF
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

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


