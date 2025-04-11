---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions-Klasse. Stellt Optionen für den PDF-zu-XLSX-Konverter für das XlsConverter-Plugin dar
type: docs
weight: 9150
url: /de/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions-Klasse

Stellt Optionen für den PDF-zu-XLSX-Konverter für das [`XlsConverter`](../xlsconverter/) Plugin dar.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Ausgabeformat. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Gibt die Datensammlung des PdfConverterOptions-Plugins zurück. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Setzen Sie true, wenn Sie das Einfügen einer leeren Spalte als erste Spalte des Arbeitsblatts benötigen. Der Standardwert ist false; das bedeutet, dass keine leere Spalte eingefügt wird. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter in der resultierenden Arbeitsmappe minimieren möchten. Der Standardwert ist false; das bedeutet, dass jede PDF-Seite als separates Arbeitsblatt gespeichert wird. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Gibt die Sammlung der hinzugefügten Ziele für die Speicherung der Operationsergebnisse zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Fügt der Datensammlung des PdfConverter-Plugins eine neue Datenquelle hinzu. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Fügt der Datensammlung des PdfToXLSXConverterOptions-Plugins eine neue Datenquelle hinzu. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Ermöglicht die Angabe des Dateiformats .xlsx, .xls/xml oder csv. Der Standardwert ist XLSX. |

### Siehe auch

* Klasse [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)