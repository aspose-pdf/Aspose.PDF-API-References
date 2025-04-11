---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer klass. Representerar en klass för att producera PDF från andra format. Detta exempel visar hur man producerar en Pdf-fil från en CGM-fil
type: docs
weight: 4610
url: /sv/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer klass

Representerar en klass för att producera PDF från andra format. Detta exempel visar hur man producerar en Pdf-fil från en CGM-fil.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Success produced pdf file.
}
catch (InvalidCgmFileFormatException e)
{
    //  Do something...
}
```

```csharp
public abstract class PdfProducer
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Producera PDF-strömmen med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Producera PDF-filen med angivet importformat. Detta exempel visar hur man producerar Pdf-fil från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Producera PDF-filen med angiven importoption. Detta exempel visar hur man producerar Pdf-ström från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Producera PDF-filen med angiven importoption. Detta exempel visar hur man producerar Pdf-fil från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Producera PDF-strömmen med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Producera PDF-filen med angivet importformat. Detta exempel visar hur man producerar Pdf-fil från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Producera PDF-strömmen med angiven importoption. Detta exempel visar hur man producerar Pdf-ström från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Producera PDF-filen med angiven importoption. Detta exempel visar hur man producerar Pdf-fil från CGM-fil. |

### Se Även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)