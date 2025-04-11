---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.PdfToImageOptions. Mewakili opsi untuk plugin PdfToImage
type: docs
weight: 9130
url: /id/net/aspose.pdf.plugins/pdftoimageoptions/
---
## Kelas PdfToImageOptions

Mewakili opsi untuk plugin [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Mendapatkan mode konversi gambar. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Mengembalikan koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Mengembalikan nama operasi. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Mendapatkan atau mengatur nilai resolusi dari gambar yang dihasilkan. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Mendapatkan atau mengatur daftar halaman untuk proses. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Mengatur sumber data simpan baru. Hanya bisa berupa . Jika Anda ingin menyimpan gambar ke dalam aliran memori, lewati null sebagai parameter. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Mendefinisikan berbagai mode yang dapat digunakan saat mengonversi dari dokumen PDF ke gambar Jpeg. Lihat kelas [`JpegOptions`](../jpegoptions/). |

## Catatan

Kelas PdfImageOptions berisi fungsi dasar untuk menambahkan data (file, aliran) yang mewakili dokumen PDF input.

### Lihat Juga

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)