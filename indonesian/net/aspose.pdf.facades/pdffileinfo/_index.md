---
title: "Kelas PdfFileInfo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.PdfFileInfo. Mewakili kelas untuk mengakses informasi meta dari dokumen PDF"
type: docs
weight: 4640
url: /id/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Mewakili kelas untuk mengakses informasi meta dokumen PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Menginisialisasi objek `PdfFileInfo` baru berdasarkan *dokumen*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Mendapatkan atau mengatur informasi Penulis dari dokumen PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Mendapatkan atau mengatur informasi CreationDate dari dokumen PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Mendapatkan atau mengatur informasi Creator dari dokumen PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Mengembalikan true jika file input saat ini adalah file 'Portfolio' yang berisi kumpulan file PDF di dalamnya. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Mengembalikan true jika password diperlukan untuk mengubah izin atau properti keamanan dokumen. Perhatikan bahwa properti ini hanya dapat dibaca jika password yang valid diberikan dalam konstruktor `PdfFileInfo`. Jika PasswordType adalah Inaccessible (artinya password yang tidak valid diberikan) pembacaan properti ini akan gagal dengan [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Mengembalikan true jika password diperlukan untuk membuka dokumen PDF yang dilindungi password. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Mendapatkan atau mengatur informasi yang disesuaikan dari dokumen PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Memeriksa apakah dokumen PDF terenkripsi. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Memeriksa apakah sumber input adalah file PDF yang valid. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Mendapatkan atau mengatur informasi Keywords dari dokumen PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Mendapatkan atau mengatur informasi tanggal ModDate dari dokumen PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Mendapatkan jumlah halaman dokumen. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Mengembalikan jenis password yang diberikan untuk membuat instance PdfFileInfo. Lihat nilai yang mungkin di [`PasswordType`](./passwordtype/). Perhatikan bahwa dokumen pdf dapat dibuka menggunakan password pengguna (atau buka) dan password pemilik (atau izin, edit). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Mendapatkan informasi Producer dari dokumen PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Mendapatkan atau mengatur informasi Subject dari dokumen PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Mendapatkan atau mengatur informasi Title dari dokumen PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Menggunakan aturan validasi ketat melalui properti [`IsPdfFile`](./ispdffile/). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Membersihkan semua informasi meta dari dokumen PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Mendeinisialisasi instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Mengambil pengaturan hak istimewa dokumen PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Mengambil informasi yang disesuaikan dari dokumen PDF dengan nama properti. Jika tidak ada properti yang cocok dengan nama tersebut, akan mengembalikan string kosong. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Mengambil tinggi halaman yang ditentukan. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Mengambil rotasi halaman yang ditentukan. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Mengambil lebar halaman yang ditentukan. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Mengambil offset horizontal area tampilan halaman yang ditentukan. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Mengambil offset vertikal area tampilan halaman yang ditentukan. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Mengambil info versi dokumen PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Menyimpan dokumen PDF ke file yang ditentukan. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Menyimpan dokumen PDF yang diperbarui ke file yang ditentukan. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Mengubah properti yang ditentukan secara eksplisit dengan mengatur informasi file, properti lain tetap. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Mengatur informasi yang disesuaikan dari dokumen PDF. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


