---
title: "Class HtmlLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.HtmlLoadOptions class. Rappresenta le opzioni per il caricamento/importazione di un file html in pdf document"
type: docs
weight: 5660
url: /it/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Crea le opzioni di caricamento per convertire html in pdf document con percorso base vuoto. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Crea le opzioni di caricamento per convertire html in pdf document con percorso base definito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Il percorso/base URL per il file html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Ottiene o imposta i possibili tipi di media utilizzati durante il rendering. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Restituisce o imposta l'attributo che specifica la codifica utilizzata per questo document al momento dell'analisi. Se questo attributo è null, la codifica verrà determinata dal set di caratteri del document. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Restituisce o imposta l'incorporamento dei font nel result document |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Restituisce o imposta il flag che specifica che le regole @page definite in css sovrascriveranno i valori definiti in PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Restituisce o imposta il rendering di tutto il document in una singola pagina |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Restituisce o imposta le informazioni della pagina del document |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Ottiene o imposta l'opzione di layout. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | A volte è necessario evitare l'uso del loader interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDF in cloud l'accesso diretto ai file di riferimento è impossibile: in tal caso dovrebbe essere utilizzato del codice personalizzato inserito in un metodo speciale, e il delegato che fa riferimento a quel metodo dovrebbe essere assegnato a questo attributo. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Se il caricamento di dati esterni referenziati in HTML richiede credenziali, è possibile inserirle in questo parametro: verranno utilizzate durante il caricamento delle risorse esterne. |

## Esempi

Il seguente esempio mostra come convertire un file HTML in un file PDF

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file HTML.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Inizializza HtmlLoadOptions\t
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Salva file PDF
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

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


