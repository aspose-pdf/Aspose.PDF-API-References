---
title: PdfProducer
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per produrre PDF da altri formati.  Questo esempio mostra come produrre file Pdf da file CGM.
type: docs
weight: 2620
url: /it/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Rappresenta una classe per produrre PDF da altri formati.  Questo esempio mostra come produrre file Pdf da file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    //Il TestPath potrebbe essere riassegnato.
}
catch (InvalidCgmFileFormatException e)
{
    //Il TestPath potrebbe essere riassegnato.
}
```

```csharp
public abstract class PdfProducer
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce)(Stream, ImportFormat, Stream) | Produci il flusso PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre stream Pdf da stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_1)(Stream, ImportFormat, string) | Produci il file PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre file Pdf dal flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_2)(Stream, ImportOptions, Stream) | Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre stream Pdf da stream CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_3)(Stream, ImportOptions, string) | Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre file Pdf dal flusso CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_4)(string, ImportFormat, Stream) | Produci il flusso PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre un flusso Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_5)(string, ImportFormat, string) | Produci il file PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre file Pdf da file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_6)(string, ImportOptions, Stream) | Produci il flusso PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre un flusso Pdf da un file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_7)(string, ImportOptions, string) | Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre file Pdf da file CGM. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->