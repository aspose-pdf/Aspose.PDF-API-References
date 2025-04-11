---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfToXlsOptions. Rappresenta le opzioni del convertitore da PDF a XLSX per il plugin XlsConverter
type: docs
weight: 9150
url: /it/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## Classe PdfToXlsOptions

Rappresenta le opzioni del convertitore da PDF a XLSX per il plugin [`XlsConverter`](../xlsconverter/).

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
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Imposta su true se è necessario inserire una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è false; significa che la colonna vuota non sarà inserita. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Imposta su true se è necessario minimizzare il numero di fogli di lavoro nel workbook risultante. Il valore predefinito è false; significa salvare ogni pagina PDF come foglio di lavoro separato. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Ottiene il nome dell'operazione. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Ottiene la raccolta degli obiettivi aggiunti per i risultati dell'operazione di salvataggio. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente dati alla raccolta di dati del plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Aggiunge una nuova sorgente dati alla raccolta di dati del plugin PdfToXLSXConverterOptions. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Consente di specificare il formato file .xlsx, .xls/xml o csv. Il valore predefinito è XLSX. |

### Vedi Anche

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)