---
title: "Kelas PdfPageEditor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.PdfPageEditor. Mewakili kelas untuk mengedit halaman file PDF termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman."
type: docs
weight: 4710
url: /id/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Hashtable berisi nomor halaman dan derajat rotasi, kunci mewakili nomor halaman, nilai kunci mewakili rotasi dalam derajat. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Mendapatkan atau mengatur ukuran halaman file output. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Mendapatkan atau mengatur nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Mendapatkan atau mengatur rotasi halaman, rotasi harus 0, 90, 180, atau 270. Nilai default adalah 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Mendapatkan atau mengatur durasi efek transisi. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Mendapatkan atau mengatur gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Mendapatkan atau Mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Mendapatkan atau mengatur koefisien zoom. Nilai 1.0 sesuai dengan 100%. Nilai default adalah 1.0. Contoh berikut menunjukkan cara mengubah zoom halaman document. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Terapkan perubahan yang dibuat pada halaman document. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Membuang Aspose.Pdf.Document yang terikat dengan sebuah facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Mengembalikan ukuran kotak yang ditentukan dalam document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Mengembalikan rotasi halaman yang ditentukan. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Mengembalikan total jumlah halaman. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Mengembalikan ukuran halaman dari halaman yang ditentukan. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Memindahkan asal dari (0, 0) ke titik yang ditunjuk. Asal berada di kiri-bawah dan satuannya adalah point (1 inci = 72 point). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Menyimpan document yang diubah ke dalam stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Menyimpan document yang diubah ke dalam file. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Tirai Vertikal |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Tirai Vertikal |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Usap Bawah ke Atas |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Kilau Diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Halaman lama menghilang |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Kotak Masuk |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Kilau Kiri-Kanan |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Usap Kiri ke Kanan |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Kotak Keluar |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Usap Kanan ke Kiri |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Pemisahan Horizontal IN |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Pemisahan Horizontal Out |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Dalam Pembagian Vertikal |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Luar Pembagian Vertikal |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Glitter Atas-Bawah |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Usap Atas-Bawah |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


