---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.HtmlLoadOptions. Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf
type: docs
weight: 5530
url: /it/net/aspose.pdf/htmlloadoptions/
---
## Classe HtmlLoadOptions

Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Crea opzioni di caricamento per convertire html in un documento pdf con percorso base vuoto. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Crea opzioni di caricamento per convertire html in un documento pdf con percorso base definito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Il percorso/base url per il file html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Ottiene o imposta i possibili tipi di media utilizzati durante il rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Ottiene o imposta l'attributo che specifica la codifica utilizzata per questo documento al momento dell'analisi. Se questo attributo è nullo, la codifica sarà determinata dall'attributo del set di caratteri del documento. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Ottiene o imposta l'incorporamento dei caratteri nel documento risultante |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Ottiene o imposta il flag che specifica che le regole @page definite in css sovrascriveranno i valori definiti in PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Ottiene o imposta il rendering di tutto il documento su una singola pagina |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Ottiene o imposta le informazioni sulla pagina del documento |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Ottiene o imposta l'opzione di layout. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | A volte è necessario evitare l'uso del caricatore interno delle risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDF nel cloud, l'accesso diretto ai file di riferimento è impossibile: in tal caso, dovrebbe essere utilizzato del codice personalizzato inserito in un metodo speciale, e il delegato che si riferisce a quel metodo dovrebbe essere assegnato a questo attributo. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Se il caricamento di dati esterni referenziati in HTML richiede credenziali, puoi inserirle in questo parametro - saranno utilizzate durante il caricamento delle risorse esterne |

## Esempi

Il seguente esempio mostra come convertire un file HTML in un file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)