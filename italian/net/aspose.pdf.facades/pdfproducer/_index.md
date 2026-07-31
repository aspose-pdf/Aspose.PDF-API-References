---
title: "Classe PdfProducer"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfProducer. Rappresenta una classe per generare PDF da altri formati. Questo esempio mostra come produrre un file Pdf da un file CGM"
type: docs
weight: 4730
url: /it/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Rappresenta una classe per produrre PDF da altri formati. Questo esempio mostra come produrre un file Pdf da un file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // File pdf prodotto con successo.
}
catch (InvalidCgmFileFormatException e)
{
    //  Esegui qualcosa...
}
```

```csharp
public abstract class PdfProducer
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Genera lo stream PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre lo stream Pdf da uno stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Genera il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da uno stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Genera il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre lo stream Pdf da uno stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Genera il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da uno stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Genera lo stream PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre lo stream Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Genera il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Genera lo stream PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre lo stream Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Genera il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da un file CGM. |

### Vedi anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


