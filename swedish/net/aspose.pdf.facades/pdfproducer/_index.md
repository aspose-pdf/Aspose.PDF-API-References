---
title: PdfProducer
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att producera PDF från andra format.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil.
type: docs
weight: 2620
url: /sv/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Representerar en klass för att producera PDF från andra format.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Framgång producerad pdf-fil.
}
catch (InvalidCgmFileFormatException e)
{
    // Göra någonting...
}
```

```csharp
public abstract class PdfProducer
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce)(Stream, ImportFormat, Stream) | Producera PDF-strömmen med angivet importformat.  Detta exempel visar hur man producerar PDF-ström från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_1)(Stream, ImportFormat, string) | Skapa PDF-filen med angivet importformat.  Det här exemplet visar hur man skapar en pdf-fil från CGM stream. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_2)(Stream, ImportOptions, Stream) | Skapa PDF-filen med det angivna importalternativet.  Detta exempel visar hur man producerar PDF-ström från CGM-ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_3)(Stream, ImportOptions, string) | Skapa PDF-filen med det angivna importalternativet.  Det här exemplet visar hur man skapar en pdf-fil från CGM stream. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_4)(string, ImportFormat, Stream) | Producera PDF-strömmen med angivet importformat.  Detta exempel visar hur man producerar PDF-ström från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_5)(string, ImportFormat, string) | Skapa PDF-filen med angivet importformat.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_6)(string, ImportOptions, Stream) | Producera PDF-strömmen med det angivna importalternativet.  Detta exempel visar hur man producerar PDF-ström från CGM-fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_7)(string, ImportOptions, string) | Skapa PDF-filen med det angivna importalternativet.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil. |

### Se även

* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->