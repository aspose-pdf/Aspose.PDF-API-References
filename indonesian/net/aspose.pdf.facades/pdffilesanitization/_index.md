---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileSanitization. Mewakili API sanitasi dan pemulihan. Gunakan ini jika Anda tidak dapat membuat/membuka dokumen dengan cara lain
type: docs
weight: 4540
url: /id/net/aspose.pdf.facades/pdffilesanitization/
---
## Kelas PdfFileSanitization

Mewakili API sanitasi dan pemulihan. Gunakan ini jika Anda tidak dapat membuat/membuka dokumen dengan cara lain.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Setelah file disimpan, Anda dapat memeriksa apa yang telah dilakukan dengan file. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Memungkinkan untuk menghasilkan xref dan trailer baru untuk dokumen. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Memungkinkan untuk menghapus data setelah data pdf |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Memungkinkan untuk menghapus data sebelum data pdf. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Mengikat aliran Pdf untuk Sanitasi. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Mengikat file Pdf untuk Sanitasi. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Menutup facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Menghapus xref lama dengan trailer dan membuat xref baru dengan trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Memulihkan dokumen. Gunakan properti untuk menyesuaikan. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Menyimpan PDF hasil ke aliran. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Menyimpan PDF hasil ke file. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Menghapus data setelah %%EOF terakhir. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Menghapus data sebelum %PDF. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)