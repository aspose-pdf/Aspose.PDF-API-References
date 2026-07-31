---
title: "Kelas PdfToImageOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.PdfToImageOptions. Menyatakan opsi untuk plugin PdfToImage"
type: docs
weight: 9280
url: /id/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Menyatakan opsi untuk plugin [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Mendapatkan mode konversi gambar. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Mengembalikan koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Mengembalikan nama operasi. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Mendapatkan atau mengatur nilai resolusi gambar yang dihasilkan. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Mendapatkan atau mengatur daftar halaman untuk proses. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Mengatur sumber data penyimpanan baru. Hanya dapat berupa . Jika Anda ingin menyimpan gambar ke aliran memori, berikan null sebagai parameter. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Menentukan berbagai mode yang dapat digunakan saat mengonversi dokumen PDF ke gambar Jpeg. Lihat kelas [`JpegOptions`](../jpegoptions/). |

## Catatan

Kelas PdfImageOptions berisi fungsi dasar untuk menambahkan data (file, aliran) yang mewakili input PDF documents.

### Lihat Juga

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


