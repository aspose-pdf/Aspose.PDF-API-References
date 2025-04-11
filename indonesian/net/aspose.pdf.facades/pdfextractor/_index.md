---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfExtractor. Kelas untuk mengekstrak gambar dan teks dari dokumen PDF
type: docs
weight: 4450
url: /id/net/aspose.pdf.facades/pdfextractor/
---
## Kelas PdfExtractor

Kelas untuk mengekstrak gambar dan teks dari dokumen PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Menginisialisasi objek `PdfExtractor` baru. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Menginisialisasi objek `PdfExtractor` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Mendapatkan atau mengatur halaman akhir dalam rentang halaman di mana operasi ekstraksi akan dilakukan. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Mengatur mode untuk proses ekstraksi gambar. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Mengatur mode untuk hasil ekstraksi teks. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Benar jika teks memiliki simbol Ibrani atau Arab. Kasus ini harus dipertimbangkan secara khusus karena fungsi string mengubah perilakunya dan mulai memproses teks dari kanan ke kiri (kecuali angka dan karakter non-teks lainnya). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Mendapatkan atau mengatur kata sandi file input. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Mengatur atau mendapatkan resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar yang memiliki nilai resolusi lebih tinggi lebih jelas. Namun, meningkatkan nilai resolusi mengakibatkan peningkatan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya, untuk mendapatkan gambar yang jelas, cukup mengatur resolusi ke 150 atau 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Mendapatkan atau mengatur halaman awal dalam rentang halaman di mana operasi ekstraksi akan dilakukan. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Mengikat dokumen PDF dari stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Mengikat file PDF input. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Menghapus Aspose.Pdf.Document yang terikat dengan facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Mengekstrak lampiran dari dokumen Pdf. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Mengekstrak lampiran ke file PDF berdasarkan nama lampiran. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Mengekstrak gambar dari file PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Mengekstrak teks dari dokumen Pdf menggunakan encoding Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Mengekstrak teks dari dokumen Pdf menggunakan encoding yang ditentukan. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Menyimpan semua file lampiran ke stream. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Menyimpan lampiran ke dalam file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Mendapatkan daftar lampiran. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream dengan format gambar yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Menyimpan teks satu halaman ke stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Menyimpan teks satu halaman ke file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Menyimpan teks ke stream. lihat juga:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Menyimpan teks ke file. lihat juga:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Menyimpan teks ke stream. lihat juga:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Menunjukkan apakah dapat mendapatkan lebih banyak teks atau tidak. |

### Lihat Juga

* kelas [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)