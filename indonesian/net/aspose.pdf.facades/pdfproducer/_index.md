---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfProducer. Mewakili kelas untuk memproduksi PDF dari format lain. Contoh ini menunjukkan cara memproduksi file Pdf dari file CGM
type: docs
weight: 4610
url: /id/net/aspose.pdf.facades/pdfproducer/
---
## Kelas PdfProducer

Mewakili kelas untuk memproduksi PDF dari format lain. Contoh ini menunjukkan cara memproduksi file Pdf dari file CGM.

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

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Memproduksi aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara memproduksi aliran Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Memproduksi file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara memproduksi file Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Memproduksi file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara memproduksi aliran Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Memproduksi file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara memproduksi file Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Memproduksi aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara memproduksi aliran Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Memproduksi file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara memproduksi file Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Memproduksi aliran PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara memproduksi aliran Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Memproduksi file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara memproduksi file Pdf dari file CGM. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)