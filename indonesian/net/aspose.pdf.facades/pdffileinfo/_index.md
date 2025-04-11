---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileInfo. Mewakili kelas untuk mengakses informasi meta dari dokumen PDF
type: docs
weight: 4520
url: /id/net/aspose.pdf.facades/pdffileinfo/
---
## Kelas PdfFileInfo

Mewakili kelas untuk mengakses informasi meta dari dokumen PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Menginisialisasi objek `PdfFileInfo` baru berdasarkan *dokumen*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Mendapatkan atau mengatur informasi Penulis dari dokumen PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Mendapatkan atau mengatur informasi TanggalPembuatan dari dokumen PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Mendapatkan atau mengatur informasi Pembuat dari dokumen PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Mengembalikan true jika file input saat ini adalah file 'Portfolio' yang berisi koleksi file PDF di dalamnya. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Mengembalikan true jika kata sandi diperlukan untuk memodifikasi izin atau properti keamanan dokumen. Perhatikan bahwa properti ini hanya dapat dibaca jika kata sandi yang valid diberikan dalam konstruktor `PdfFileInfo`. Jika PasswordType tidak dapat diakses (berarti kata sandi yang tidak valid diberikan), membaca properti ini akan gagal dengan [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Mengembalikan true jika kata sandi diperlukan untuk membuka dokumen pdf yang dilindungi kata sandi. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Mendapatkan atau mengatur informasi kustom dari dokumen PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Memeriksa apakah dokumen PDF terenkripsi. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Memeriksa apakah input sumber adalah file PDF yang valid. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Mendapatkan atau mengatur informasi KataKunci dari dokumen PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Mendapatkan atau mengatur informasi tanggal ModDate dari dokumen PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Mendapatkan jumlah halaman dokumen. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Mengembalikan jenis kata sandi yang diberikan untuk membuat instance PdfFileInfo. Lihat nilai yang mungkin dalam [`PasswordType`](./passwordtype/). Perhatikan bahwa dokumen pdf dapat dibuka menggunakan kata sandi pengguna (atau buka) dan kata sandi pemilik (atau izin, edit). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Mendapatkan informasi Produser dari dokumen PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Mendapatkan atau mengatur informasi Subjek dari dokumen PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Mendapatkan atau mengatur informasi Judul dari dokumen PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Menggunakan aturan validasi ketat melalui penggunaan properti [`IsPdfFile`](./ispdffile/). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Menghapus semua informasi meta dari dokumen PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Menginisialisasi ulang instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Mendapatkan pengaturan hak istimewa dokumen PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Mendapatkan informasi kustom dari dokumen PDF dengan nama properti. Jika tidak ada properti yang cocok dengan nama, akan mengembalikan string kosong. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Mendapatkan tinggi halaman yang ditentukan. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Mendapatkan rotasi halaman yang ditentukan. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Mendapatkan lebar halaman yang ditentukan. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Mendapatkan offset horizontal dari area tampilan halaman yang ditentukan. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Mendapatkan offset vertikal dari area tampilan halaman yang ditentukan. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Mendapatkan informasi versi dari dokumen PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Menyimpan dokumen PDF ke file yang ditentukan. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Menyimpan dokumen PDF yang diperbarui ke file yang ditentukan. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Mengubah properti yang ditentukan secara eksplisit dengan mengatur informasi file, properti lainnya tetap. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Mengatur informasi kustom dari dokumen PDF. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)