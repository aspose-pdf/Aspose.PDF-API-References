---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfConverter. Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar yang mendukung BMP, JPEG, PNG, dan TIFF sekarang. Konten yang didukung dalam pdf: gambar, formulir, komentar.
type: docs
weight: 4440
url: /id/net/aspose.pdf.facades/pdfconverter/
---
## Kelas PdfConverter

Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, mendukung BMP, JPEG, PNG, dan TIFF sekarang. Konten yang didukung dalam pdf: gambar, formulir, komentar.

```csharp
public sealed class PdfConverter : Facade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Menginisialisasi objek `PdfConverter` baru. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Menginisialisasi objek `PdfConverter` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Mendapatkan atau mengatur posisi akhir yang ingin Anda konversi. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Mendapatkan jumlah halaman. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Mendapatkan atau mengatur OwnerPassword dokumen. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Mendapatkan atau mengatur resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Mendapatkan atau mengatur posisi awal yang ingin Anda konversi. Nilai minimal adalah 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Mendapatkan atau mengatur UserPassword dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Mengikat Pdf Stream untuk konversi. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Mengikat file Pdf untuk konversi. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Menutup instance PdfConverter dan melepaskan sumber daya. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Melakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Menyimpan gambar ke stream dengan format gambar default - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Menyimpan gambar ke file dengan format gambar default - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Menyimpan gambar ke stream dengan format gambar yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Menyimpan gambar ke stream dengan ukuran halaman yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Menyimpan gambar ke file dengan format gambar yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar default - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Menyimpan gambar ke stream dengan format gambar dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Menyimpan gambar ke stream dengan ukuran halaman yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Menyimpan gambar ke file dengan format gambar dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Menyimpan gambar ke file dengan ukuran halaman dan format gambar yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Menyimpan gambar ke stream dengan format gambar, ukuran, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Menyimpan gambar ke stream dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Menyimpan gambar ke file dengan format gambar dan dimensi yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Menyimpan gambar ke file dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Menyimpan gambar ke stream dengan format gambar, ukuran, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Menyimpan gambar ke stream dengan format gambar, dimensi, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Menyimpan gambar ke file dengan format gambar, ukuran gambar, dan kualitas yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Menunjukkan apakah file pdf memiliki lebih banyak gambar atau tidak. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke dalam satu file TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke dalam satu file TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Menggabungkan daftar stream gambar menjadi satu stream gambar. Format keluaran png/jpg/tiff didukung, jika menggunakan format keluaran yang tidak didukung, stream keluaran akan dikodekan sebagai Jpeg secara default. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Menggabungkan daftar stream tiff menjadi satu stream tiff dengan beberapa frame. |

### Lihat Juga

* kelas [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)