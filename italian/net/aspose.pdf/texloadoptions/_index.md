---
title: "Classe TeXLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.TeXLoadOptions. Rappresenta le opzioni per il caricamento/importazione di file TeX in un documento PDF"
type: docs
weight: 10550
url: /it/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file TeX in un documento PDF.

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
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Ottiene/Imposta un certo valore per i primitivi data/ora come anno, mese, giorno e ora. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Ottiene/Imposta la directory di input TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Ottiene/Imposta il nome del lavoro. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Ottiene/Imposta un flag che annulla le legature in tutti i caratteri. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Ottiene/Imposta la directory di output TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Ottiene/Imposta un flag che consente di rasterizzare le formule matematiche. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Ottiene/Imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, vi siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario al primo avvio. Al secondo avvio, il motore utilizza in qualche modo tali dati. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Ottiene/Imposta la directory di input richiesta da TeX. L'input richiesto sono i file che sono in qualche modo inclusi nel file .tex principale, ad esempio pacchetti per i quali non esiste supporto integrato. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Ottiene/Imposta il flag che indica se mostrare l'output del terminale sulla console. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Ottiene/Imposta il flag che indica se suddividere i caratteri nel file di output o meno. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Ottiene il risultato del caricamento e della compilazione TeX - tutto è andato senza problemi o ci sono stati commenti/errori. |

## Esempi

Il seguente esempio mostra come convertire un file TeX in un file PDF

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il percorso al tuo file TeX.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Inizializza TeXLoadOptions\t
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Salva file PDF
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

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


