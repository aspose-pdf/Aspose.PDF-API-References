---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfProducer. Representa uma classe para produzir PDF a partir de outros formatos. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM
type: docs
weight: 4610
url: /pt/net/aspose.pdf.facades/pdfproducer/
---
## Classe PdfProducer

Representa uma classe para produzir PDF a partir de outros formatos. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM.

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

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Produz o fluxo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um fluxo Pdf a partir de um fluxo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Produz o arquivo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um arquivo Pdf a partir de um fluxo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Produz o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um fluxo Pdf a partir de um fluxo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Produz o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um arquivo Pdf a partir de um fluxo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Produz o fluxo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um fluxo Pdf a partir de um arquivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Produz o arquivo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Produz o fluxo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um fluxo Pdf a partir de um arquivo CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Produz o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM. |

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)