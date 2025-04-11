---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions klass. Representerar PDF till XLSX-konverteringsalternativ för XlsConverter-plugin
type: docs
weight: 9150
url: /sv/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions klass

Representerar PDF till XLSX-konverteringsalternativ för [`XlsConverter`](../xlsconverter/) plugin.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Utdataformat. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Returnerar PdfConverterOptions plugin datainsamling. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Sätt till true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att en tom kolumn inte kommer att infogas. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Sätt till true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat kalkylblad. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Hämtar namnet på operationen. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Hämtar samling av tillagda mål för att spara operationens resultat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Lägger till en ny datakälla till PdfConverter plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Lägger till en ny datakälla till PdfToXLSXConverterOptions plugin datainsamling. |

## Andra Medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Möjliggör att specificera .xlsx, .xls/xml eller csv filformat. Standardvärdet är XLSX. |

### Se Även

* klass [PdfConverterOptions](../pdfconverteroptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* sammansättning [Aspose.PDF](../../)