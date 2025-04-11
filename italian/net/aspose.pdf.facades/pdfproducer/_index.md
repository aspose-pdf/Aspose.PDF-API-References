---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfProducer. Rappresenta una classe per produrre PDF da altri formati. Questo esempio mostra come produrre un file Pdf da un file CGM
type: docs
weight: 4610
url: /it/net/aspose.pdf.facades/pdfproducer/
---
## Classe PdfProducer

Rappresenta una classe per produrre PDF da altri formati. Questo esempio mostra come produrre un file Pdf da un file CGM.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Produce il flusso PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un flusso Pdf da un flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Produce il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da un flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un flusso Pdf da un flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da un flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Produce il flusso PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un flusso Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Produce il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Produce il flusso PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un flusso Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da un file CGM. |

### Vedi Anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)