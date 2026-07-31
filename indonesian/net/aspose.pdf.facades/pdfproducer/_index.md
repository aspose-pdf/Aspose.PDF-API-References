---
title: "Kelas PdfProducer"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.PdfProducer. Mewakili kelas untuk menghasilkan PDF dari format lain. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM"
type: docs
weight: 4730
url: /id/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Mewakili kelas untuk menghasilkan PDF dari format lain. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Berhasil menghasilkan file pdf.
}
catch (InvalidCgmFileFormatException e)
{
    //  Lakukan sesuatu...
}
```

```csharp
public abstract class PdfProducer
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Hasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Hasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Hasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Hasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Hasilkan aliran PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


