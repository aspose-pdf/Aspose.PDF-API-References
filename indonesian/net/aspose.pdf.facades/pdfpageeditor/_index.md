---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfPageEditor. Mewakili kelas untuk mengedit halaman file PDF termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman
type: docs
weight: 4590
url: /id/net/aspose.pdf.facades/pdfpageeditor/
---
## Kelas PdfPageEditor

Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Konstruktor untuk kelas PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Konstruktor untuk kelas PdfPageEditor. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Mendapatkan atau mengatur durasi tampilan untuk halaman. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal konten PDF asli di halaman hasil, default adalah AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Sebuah hashtable yang berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Mendapatkan atau mengatur ukuran halaman file keluaran. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Mendapatkan atau mengatur nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Mendapatkan atau mengatur rotasi halaman, rotasi harus 0, 90, 180 atau 270. Nilai default adalah 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Mendapatkan atau mengatur durasi efek transisi. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Mendapatkan atau mengatur gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Mendapatkan atau mengatur perataan vertikal konten PDF asli di halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Mendapatkan atau mengatur koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0. Contoh berikut menunjukkan cara mengubah zoom halaman dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Menerapkan perubahan yang dilakukan pada halaman dokumen. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Menghapus Aspose.Pdf.Document yang terikat dengan facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Mengembalikan ukuran kotak yang ditentukan dalam dokumen. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Mengembalikan rotasi halaman yang ditentukan. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Mengembalikan total jumlah halaman. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Mengembalikan ukuran halaman dari halaman yang ditentukan. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Memindahkan titik asal dari (0, 0) ke titik yang ditentukan. Titik asal berada di kiri-bawah dan satuan adalah point (1 inci = 72 point). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Menyimpan dokumen yang telah diubah ke dalam stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Menyimpan dokumen yang telah diubah ke dalam file. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Tirai Vertikal |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Tirai Vertikal |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Usap Bawah-Atas |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Glitter Diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Halaman lama larut |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Kotak Masuk |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Glitter Kiri-Kanan |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Usap Kiri-Kanan |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Kotak Keluar |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Usap Kanan-Kiri |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Pembagian Horizontal Dalam |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Pembagian Horizontal Keluar |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Pembagian Vertikal Dalam |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Pembagian Vertikal Keluar |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Glitter Atas-Bawah |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Usap Atas-Bawah |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)