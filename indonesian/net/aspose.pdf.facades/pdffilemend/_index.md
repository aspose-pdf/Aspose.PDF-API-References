---
title: "Kelas PdfFileMend"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Facades.PdfFileMend class. Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada"
type: docs
weight: 4650
url: /id/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Konstruktor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Menginisialisasi objek `PdfFileMend` baru berdasarkan *document*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Mengatur nilai bool yang menunjukkan pembungkus kata pada metode AddText. Jika nilai true, teks dalam FormattedText akan dibungkus. Secara default, nilai adalah false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Mengatur atau mengambil strategi penempatan teks. [`PositioningMode`](../positioningmode/) Mode default adalah Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Mengatur atau mengambil algoritma pembungkus kata. Lihat WordWrapMode dan IsWordWrap. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Menambahkan gambar ke halaman-halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Tidak diimplementasikan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Tidak diimplementasikan. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Tidak diimplementasikan. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Menutup objek PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


