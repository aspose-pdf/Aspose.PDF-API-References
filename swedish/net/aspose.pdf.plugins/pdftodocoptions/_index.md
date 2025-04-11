---
title: Class PdfToDocOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToDocOptions klass. Representerar PDF till DOC-konverteringsalternativ för DocConverter-plugin
type: docs
weight: 9090
url: /sv/net/aspose.pdf.plugins/pdftodocoptions/
---
## PdfToDocOptions klass

Representerar PDF till DOC-konverteringsalternativ för [`DocConverter`](../docconverter/) plugin.

```csharp
public sealed class PdfToDocOptions : PdfConverterOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfToDocOptions](pdftodocoptions/#constructor)() | Initierar en ny instans av `PdfToDocOptions`-objektet med standardalternativ. |
| [PdfToDocOptions](pdftodocoptions/#constructor_1)(SaveFormat, ConversionMode) | Initierar en ny instans av `PdfToDocOptions`-objektet för det angivna formatet och läget. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftodocoptions/conversionmode/) { get; set; } | Möjliggör kontroll över hur ett PDF-dokument konverteras till ett ordbehandlingsdokument. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Returnerar PdfConverterOptions plugin-datakollektion. |
| override [OperationName](../../aspose.pdf.plugins/pdftodocoptions/operationname/) { get; } | Hämtar namnet på operationen. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Hämtar samling av tillagda mål för att spara operationens resultat. |
| [SaveFormat](../../aspose.pdf.plugins/pdftodocoptions/saveformat/) { get; set; } | Spara format av det utgående dokumentet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Lägger till en ny datakälla till PdfConverter-pluginens datakollektion. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Lägger till en ny datakälla till PdfToXLSXConverterOptions-pluginens datakollektion. |

### Se Även

* klass [PdfConverterOptions](../pdfconverteroptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)