---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractorOptions klass. Representerar alternativ för TextExtractor och ImageExtractor plugins
type: docs
weight: 9070
url: /sv/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions klass

Representerar alternativ för TextExtractor och ImageExtractor plugins.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Returnerar PdfExtractor plugin datainsamling. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Returnerar operationsnamn |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Lägger till ny datakälla till PdfExtractor plugin datainsamling. |

## Kommentarer

Den `PdfExtractorOptions` innehåller grundläggande funktioner för att lägga till data (filer, strömmar) som representerar indata PDF-dokument. Vänligen skapa [`TextExtractorOptions`](../textextractoroptions/) eller ImageExtractorOptions istället för detta.

### Se Även

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)