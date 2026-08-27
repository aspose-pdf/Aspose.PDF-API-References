---
title: "Klass PdfProducer"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfProducer-klass. Representerar en klass för att skapa PDF från andra format. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑fil."
type: docs
weight: 4730
url: /sv/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Representerar en klass för att producera PDF från andra format. Detta exempel visar hur man producerar en Pdf-fil från en CGM-fil.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Lyckades skapa pdf‑fil.
}
catch (InvalidCgmFileFormatException e)
{
    //  Gör något...
}
```

```csharp
public abstract class PdfProducer
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Skapa PDF‑strömmen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Skapa PDF‑filen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑ström. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Skapa PDF‑strömmen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Skapa PDF‑filen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Skapa PDF‑strömmen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑fil. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑fil. |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


