---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta le opzioni per il caricamento di un file TeX in un documento PDF.
type: docs
weight: 10370
url: /it/net/aspose.pdf/texloadoptions/
---
## Classe TeXLoadOptions

Rappresenta le opzioni per il caricamento/importazione di un file TeX in un documento PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Ottiene/imposta un certo valore per i primitivi di data/ora come anno, mese, giorno e ora. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Ottiene/imposta la directory di input TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Ottiene/imposta il nome del lavoro. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Ottiene/imposta un flag che annulla le legature in tutti i caratteri. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Ottiene/imposta la directory di output TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Ottiene/imposta un flag che consente di rasterizzare le formule matematiche. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati lungo il processo di composizione e li memorizza in un file ausiliario, tutto al primo avvio. E al secondo avvio, il motore in qualche modo utilizza quei dati. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Ottiene/imposta la directory di input richiesta da TeX. L'input richiesto sono i file che sono in qualche modo inclusi nel file .tex principale, ad esempio, pacchetti per i quali non c'è supporto integrato. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Ottiene/imposta il flag che indica se suddividere i caratteri nel file di output o meno. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Ottiene il risultato per il caricamento e la compilazione di TeX - tutto è andato liscio o ci sono stati commenti/errori. |

## Esempi

Il seguente esempio mostra come convertire un file TeX in un file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)