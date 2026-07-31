---
title: "Kelas SubmitFormAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Annotations.SubmitFormAction. Kelas yang menjelaskan aksi submitform."
type: docs
weight: 2740
url: /id/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

Kelas yang menjelaskan aksi submit-form.

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
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Mendapatkan atau mengatur flag aksi submit. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Aksi berikutnya dalam urutan. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL tujuan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Mendapatkan string untuk ECMAScript Action. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Jika diatur, setiap nilai bidang yang dikirimkan yang mewakili tanggal akan dikonversi ke format standar. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Jika diatur, entri F dari FDF yang dikirimkan harus berupa spesifikasi file yang berisi aliran file tersemat yang mewakili file PDF tempat FDF dikirimkan. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Jika diatur, FDF yang dikirimkan harus mengecualikan entri F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Jika diatur, hanya akan menyertakan anotasi markup yang entri T‑nya cocok dengan nama pengguna saat ini. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Jika tidak diatur, array Fields menentukan bidang mana yang akan disertakan dalam pengiriman. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Jika diatur, nama dan nilai bidang akan dikirimkan dalam format Formulir HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Jika diatur, nama dan nilai bidang akan dikirimkan menggunakan permintaan HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Jika diatur, file FDF yang dikirim harus mencakup semua anotasi markup dalam dokumen PDF yang mendasarinya. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Jika diatur, file FDF yang dikirim harus mencakup isi semua pembaruan inkremental. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Jika diatur, semua bidang yang ditentukan oleh array Fields dan flag Include/Exclude harus dikirim. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Jika diatur, koordinat klik mouse yang menyebabkan aksi submit-form harus ditransmisikan sebagai bagian dari data formulir. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Jika diatur, dokumen harus dikirim sebagai PDF, menggunakan tipe konten MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Jika diatur, nama bidang dan nilai harus dikirim sebagai XFDF. |

### Lihat Juga

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


