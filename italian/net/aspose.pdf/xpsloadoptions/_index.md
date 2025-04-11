---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XpsLoadOptions. Rappresenta le opzioni per il caricamento/importazione di un file xps in un documento pdf
type: docs
weight: 11510
url: /it/net/aspose.pdf/xpsloadoptions/
---
## Classe XpsLoadOptions

Rappresenta le opzioni per il caricamento/importazione di un file xps in un documento pdf.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Definisce la dimensione del batch se la conversione in batch è applicabile alla coppia di formati sorgente e destinazione. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Esempi

Il seguente esempio mostra come convertire un file XPS in un file PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* interfaccia [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)