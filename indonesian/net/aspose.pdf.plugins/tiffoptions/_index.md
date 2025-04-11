---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.TiffOptions. Mewakili opsi konverter Pdf ke Tiff untuk plugin Tiff
type: docs
weight: 9420
url: /id/net/aspose.pdf.plugins/tiffoptions/
---
## Kelas TiffOptions

Mewakili opsi konverter Pdf ke Tiff untuk plugin [`Tiff`](../tiff/).

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Mendapatkan atau mengatur nilai batas transformasi warna menjadi hitam dan putih. Parameter ini dapat diterapkan dengan EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle atau ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Mendapatkan atau mengatur jenis kompresi. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Mendapatkan mode konversi gambar. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Mendapatkan atau mengatur jenis koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Mendapatkan atau mengatur kedalaman warna. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Mengembalikan koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Mengembalikan nama operasi. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Mendapatkan atau mengatur nilai resolusi dari gambar yang dihasilkan. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Mendapatkan atau mengatur daftar halaman untuk proses. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Mendapatkan dan mengatur flag yang memungkinkan untuk menyimpan semua halaman dalam satu tiff multi-halaman. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Mendapatkan atau mengatur jenis bentuk. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan melewati halaman kosong. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Mengatur sumber data simpan baru. Hanya bisa berupa . Jika Anda ingin menyimpan gambar ke dalam aliran memori, lewati null sebagai parameter. |

### Lihat Juga

* kelas [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)