---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.SubmitFormAction. Kelas yang menggambarkan aksi submitform
type: docs
weight: 2640
url: /id/net/aspose.pdf.annotations/submitformaction/
---
## Kelas SubmitFormAction

Kelas yang menggambarkan aksi submit-form.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Menginisialisasi objek SubmitFormAction. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Mendapatkan atau mengatur flagas dari aksi submit |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Aksi berikutnya dalam urutan. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL tujuan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Mendapatkan string untuk Aksi ECMAScript. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Jika diatur, nilai bidang yang dikirim yang mewakili tanggal akan dikonversi ke format standar. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Jika diatur, entri F dari FDF yang dikirim akan menjadi spesifikasi file yang berisi aliran file terbenam yang mewakili file PDF dari mana FDF dikirim. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Jika diatur, FDF yang dikirim akan mengecualikan entri F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Jika diatur, hanya akan menyertakan anotasi markup yang entri T-nya cocok dengan nama pengguna saat ini. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Jika jelas, array Fields menentukan bidang mana yang akan disertakan dalam pengiriman. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Jika diatur, nama dan nilai bidang akan dikirim dalam format Form HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Jika diatur, nama dan nilai bidang akan dikirim menggunakan permintaan HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Jika diatur, file FDF yang dikirim akan menyertakan semua anotasi markup dalam dokumen PDF yang mendasarinya. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Jika diatur, file FDF yang dikirim akan menyertakan konten dari semua pembaruan inkremental. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Jika diatur, semua bidang yang ditunjuk oleh array Fields dan flag Include/Exclude akan dikirim. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Jika diatur, koordinat klik mouse yang menyebabkan aksi submit-form akan ditransmisikan sebagai bagian dari data formulir. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Jika diatur, dokumen akan dikirim sebagai PDF, menggunakan tipe konten MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Jika diatur, nama dan nilai bidang akan dikirim sebagai XFDF. |

### Lihat Juga

* kelas [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)