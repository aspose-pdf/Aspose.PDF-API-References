---
title: "Kelas PdfExtractor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Facades.PdfExtractor class. Kelas untuk mengekstrak gambar dan teks dari dokumen PDF"
type: docs
weight: 4570
url: /id/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Mendapatkan atau mengatur halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Mengatur mode untuk proses ekstraksi gambar. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Mengatur mode untuk hasil ekstraksi teks. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Benar ketika teks memiliki simbol Ibrani atau Arab. Kasus ini harus dipertimbangkan secara khusus karena fungsi string mengubah perilakunya dan memulai proses teks dari kanan ke kiri (kecuali angka dan karakter non-teks lainnya). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Mendapatkan atau mengatur kata sandi file input. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Mengatur atau mendapatkan resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar dengan nilai resolusi lebih tinggi lebih jelas. Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Mendapatkan atau mengatur halaman mulai dalam rentang halaman tempat operasi ekstraksi akan dilakukan. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Mendapatkan atau mengatur opsi pencarian teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Mengikat dokumen PDF dari aliran. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Mengikat file PDF input. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Membuang Aspose.Pdf.Document yang terikat dengan sebuah facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Mengekstrak lampiran dari dokumen PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Mengekstrak lampiran ke file PDF berdasarkan nama lampiran. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Mengekstrak gambar dari file PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Mengekstrak teks dari dokumen Pdf menggunakan enkoding Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Mengekstrak teks dari dokumen Pdf menggunakan enkoding yang ditentukan. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Menyimpan semua file lampiran ke aliran. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Menyimpan lampiran ke file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Mendapatkan daftar lampiran. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke aliran. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke aliran dengan format gambar yang diberikan. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Menyimpan teks satu halaman ke aliran. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Menyimpan teks satu halaman ke file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Menyimpan teks ke aliran. lihat juga:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Menyimpan teks ke file. lihat juga:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Menyimpan teks ke aliran. lihat juga:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Menunjukkan apakah dapat mengambil lebih banyak teks atau tidak. |

### Lihat Juga

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


