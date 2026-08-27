---
title: "Classe PdfToXlsOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.PdfToXlsOptions. Rappresenta le opzioni del convertitore PDF in XLSX per il plugin XlsConverter"
type: docs
weight: 9300
url: /it/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

Rappresenta le opzioni del convertitore PDF in XLSX per il plugin [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Formato di output. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Restituisce la raccolta dati del plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Imposta true se è necessario inserire una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è false; ciò significa che la colonna vuota non verrà inserita. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante. Il valore predefinito è false; ciò significa che ogni pagina PDF verrà salvata come foglio di lavoro separato. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Ottiene il nome dell'operazione. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Ottiene la raccolta dei target aggiunti per salvare i risultati dell'operazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Aggiunge una nuova fonte dati alla raccolta dati del plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Aggiunge una nuova fonte dati alla raccolta dati del plugin PdfToXLSXConverterOptions. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Consente di specificare il formato file .xlsx, .xls/xml o csv. Il valore predefinito è XLSX. |

### Vedi anche

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


