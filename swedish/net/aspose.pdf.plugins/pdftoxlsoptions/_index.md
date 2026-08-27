---
title: "Klass PdfToXlsOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.PdfToXlsOptions-klass. Representerar PDF till XLSX-konverteringsalternativ för XlsConverter‑plugin"
type: docs
weight: 9300
url: /sv/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

Representerar PDF till XLSX-konverteringsalternativ för [`XlsConverter`](../xlsconverter/)‑plugin.

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
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Utdatformat. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Returnerar PdfConverterOptions-pluginens datainsamling. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Ange true om du behöver infoga en tom kolumn som den första kolumnen i kalkylbladet. Standardvärdet är false; det betyder att den tomma kolumnen inte kommer att infogas. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Ange true om du behöver minimera antalet kalkylblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat kalkylblad. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Hämtar namnet på operationen. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Hämtar samlingen av tillagda mål för att spara resultat av operationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Lägger till en ny datakälla i PdfConverter‑pluginens datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Lägger till en ny datakälla i PdfToXLSXConverterOptions‑pluginens datainsamling. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Tillåter att specificera filformatet .xlsx, .xls/xml eller csv. Standardvärdet är XLSX. |

### Se även

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


