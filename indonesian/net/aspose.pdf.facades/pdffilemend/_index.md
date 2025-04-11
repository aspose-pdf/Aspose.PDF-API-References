---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileMend. Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada
type: docs
weight: 4530
url: /id/net/aspose.pdf.facades/pdffilemend/
---
## Kelas PdfFileMend

Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Konstruktor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Menginisialisasi objek `PdfFileMend` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Mengatur nilai bool yang menunjukkan pembungkusan kata dalam metode AddText. Jika nilainya true, teks dalam FormattedText akan membungkus kata. Secara default, nilainya false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Mengatur atau mendapatkan strategi penempatan teks. [`PositioningMode`](../positioningmode/) Mode default adalah Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Mengatur atau mendapatkan algoritma pembungkusan kata. Lihat WordWrapMode dan IsWordWrap. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Belum diimplementasikan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Belum diimplementasikan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Belum diimplementasikan. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Menutup objek PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Menyimpan dokumen PDF ke stream yang ditentukan. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)