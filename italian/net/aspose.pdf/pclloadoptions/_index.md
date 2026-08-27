---
title: "Classe PclLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PclLoadOptions. Rappresenta le opzioni per il caricamento di un file PCL in un documento PDF."
type: docs
weight: 8440
url: /it/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

Rappresenta le opzioni per il caricamento (importazione) di un file PCL in un documento PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione batch è applicabile alla coppia di formati sorgente e destinazione. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Definisce il motore di conversione che sarà utilizzato per la conversione. |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Elenco degli errori di conversione. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Ottiene o imposta il valore booleano che indica se gli errori di conversione PCL devono essere soppressi. |

## Esempi

Il seguente esempio mostra come convertire un file PCL in un file PDF.

```csharp
[C#]
	// Il percorso della directory dei documenti.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il percorso del tuo file PCL.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// Il percorso del file PDF di output.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Inizializza PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Salva file PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi anche

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


