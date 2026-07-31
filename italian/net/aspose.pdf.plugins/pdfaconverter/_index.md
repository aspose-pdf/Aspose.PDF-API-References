---
title: "Classe PdfAConverter"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.PdfAConverter. Rappresenta un plugin per gestire la conversione di documenti PDF in formato PDF/A e per la convalida della conformità PDF/A"
type: docs
weight: 9150
url: /it/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Rappresenta un plugin per la gestione della conversione di documenti PDF in formato PDF/A e per la convalida della conformità PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Avvia un processo di conversione o convalida PDF/A con le opzioni fornite. |

## Esempi

L'esempio dimostra come convalidare la conformità del documento PDF al formato PDF/A (PDF/A-1a in questo caso):

```csharp
// Crea la classe delle opzioni per impostare il processo di convalida
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Aggiungi uno o più file da convalidare
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// aggiungi altri file se necessario

// Crea l'istanza del plugin
var plugin = new PdfAConverter();

// Esegui la convalida e ottieni i risultati
var resultContainer = plugin.Process(options);

// Verifica la proprietà resultContainer.ResultCollection per i risultati della convalida di ciascun file:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

L'esempio dimostra come convertire il documento PDF in un formato PDF/A (PDF/A-3b in questo caso):

```csharp
// Crea la classe delle opzioni per configurare il processo di conversione
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Aggiungi il file di origine
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Aggiungi il percorso per salvare il file convertito
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Crea l'istanza del plugin
var plugin = new PdfAConverter();

// Esegui la conversione
plugin.Process(options);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


