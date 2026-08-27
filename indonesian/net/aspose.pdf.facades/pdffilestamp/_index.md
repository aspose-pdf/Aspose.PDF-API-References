---
title: "Kelas PdfFileStamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.PdfFileStamp. Kelas untuk menambahkan cap, watermark, atau latar belakang ke file PDF."
type: docs
weight: 4690
url: /id/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Menginisialisasi objek `PdfFileStamp` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan, maka file akan disimpan dalam format PDF default tanpa konversi. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Mendapatkan atau mengatur gaya penomoran halaman. Nilai yang mungkin: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Mendapatkan atau mengatur flag optimisasi. Aliran sumber daya yang sama dalam file hasil digabung menjadi satu objek PDF jika flag ini diatur. Ini memungkinkan mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi lebih lambat dan kebutuhan memori yang lebih besar. Nilai default: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Mendapatkan tinggi halaman pertama dalam file sumber. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Mendapatkan atau mengatur rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Mendapatkan lebar halaman pertama dalam file input. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | ID cap dari cap berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Mendapatkan atau mengatur nomor mulai untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100, 101, 102... |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Menambahkan footer ke halaman dokumen. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Menambahkan gambar sebagai footer halaman. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Menambahkan gambar sebagai footer ke halaman dokumen. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Menambahkan footer ke halaman dokumen. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Menambahkan gambar sebagai footer halaman. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Menambahkan gambar sebagai footer halaman. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Menambahkan header ke halaman. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Menambahkan gambar sebagai header pada halaman. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Menambahkan gambar sebagai header ke halaman file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Menambahkan header ke halaman file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Menambahkan gambar di bagian atas halaman. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Menambahkan gambar sebagai header pada halaman. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Menambahkan nomor halaman ke halaman. Nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Menambahkan nomor halaman ke halaman-halaman. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Menambahkan nomor halaman ke halaman-halaman. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Menambahkan nomor halaman pada posisi yang ditentukan di halaman. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Menambahkan nomor halaman pada posisi yang ditentukan di halaman. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Menambahkan stempel ke file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Menutup file yang dibuka dan menyimpan perubahan. Peringatan. Jika aliran input atau output ditentukan, mereka tidak akan ditutup oleh metode Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Menyimpan dokumen ke dalam stream yang ditentukan. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Menyimpan hasil ke file yang ditentukan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Posisi kiri bawah. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Posisi tengah bawah. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Posisi kanan bawah. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Posisi kiri. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Posisi kanan. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Posisi kiri atas. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Posisi tengah atas. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Posisi kanan atas. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


