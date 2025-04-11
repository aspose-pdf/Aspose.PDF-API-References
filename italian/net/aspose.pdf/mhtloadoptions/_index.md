---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.MhtLoadOptions. Rappresenta le opzioni per il caricamento/importazione di un file .mht in un documento pdf
type: docs
weight: 6970
url: /it/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di un file .mht in un documento pdf.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | Il costruttore predefinito. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Ottiene o imposta le informazioni sulla pagina del documento |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Examples

Il seguente esempio mostra come convertire un file MHT in un file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)