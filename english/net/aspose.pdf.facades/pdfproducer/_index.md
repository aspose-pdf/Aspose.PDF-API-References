---
title: "PdfProducer Class"
linktitle: "PdfProducer"
articleTitle: "PdfProducer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfProducer class. Represents a class to produce PDF from other formats. This sample shows how to produce Pdf file from CGM file. string i..."
type: docs
weight: 500
url: "/net/aspose.pdf.facades/pdfproducer/"
keywords: "PdfProducer, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfProducer class

Represents a class to produce PDF from other formats.
 This sample shows how to produce Pdf file from CGM file.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 try
 {
 PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
 // Success produced pdf file.
 }
 catch (InvalidCgmFileFormatException e)
 {
 // Do something...
 }

```csharp
public abstract class PdfProducer
```

## Examples

This sample shows how to produce Pdf file from CGM file.

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
 // Do something...
 }
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfProducer](./pdfproducer/#constructor)(*[ImportOptions](../../aspose.pdf/importoptions/)*) | Constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Produce](./produce/)(*Stream, ImportFormat, Stream*) | Produce the PDF stream using specified import format. |
| [Produce](./produce/)(*string, ImportFormat, Stream*) | Produce the PDF stream using specified import format. |
| [Produce](./produce/)(*Stream, ImportFormat, string*) | Produce the PDF file using specified import format. |
| [Produce](./produce/)(*string, ImportFormat, string*) | Produce the PDF file using specified import format. |
| [Produce](./produce/)(*string, ImportOptions, Stream*) | Produce the PDF stream using specified import option. |
| [Produce](./produce/)(*Stream, ImportOptions, string*) | Produce the PDF file using specified import option. |
| [Produce](./produce/)(*string, ImportOptions, string*) | Produce the PDF file using specified import option. |
| [Produce](./produce/)(*Stream, ImportOptions, Stream*) | Produce the PDF file using specified import option. |

## Fields

| Name | Description |
| --- | --- |
| [options](./options/) | ImportOptions holds level of abstraction on individual import options. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

