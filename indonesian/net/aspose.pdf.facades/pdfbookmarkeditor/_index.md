---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfBookmarkEditor. Mewakili kelas untuk bekerja dengan bookmark file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus
type: docs
weight: 4420
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## Kelas PdfBookmarkEditor

Mewakili kelas untuk bekerja dengan bookmark file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Menginisialisasi objek `PdfBookmarkEditor` baru. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Menginisialisasi objek `PdfBookmarkEditor` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Menghapus Aspose.Pdf.Document yang terikat dengan facade. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Membuat bookmark untuk halaman yang ditentukan. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Membuat bookmark untuk halaman-halaman yang ditentukan. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Membuat bookmark untuk semua halaman. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Membuat bookmark yang ditentukan dalam dokumen. Metode ini dapat digunakan untuk membentuk hierarki bookmark bersarang. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Membuat bookmark untuk semua halaman dengan warna dan gaya yang ditentukan (tebal, miring). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Menghapus semua bookmark dari dokumen PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Menghapus bookmark dari dokumen PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Mengekspor bookmark ke aliran XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Mengekspor bookmark ke file XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Mengekstrak bookmark dari semua level dalam dokumen. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Mengekstrak anak-anak dari bookmark dengan judul seperti dalam bookmark yang ditentukan. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Mengekstrak bookmark dari semua level dalam dokumen. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Mengekstrak bookmark dengan judul yang ditentukan. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Mengimpor bookmark ke dokumen dari file XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Mengimpor bookmark ke dokumen dari file XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Memodifikasi judul bookmark sesuai dengan judul bookmark yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Mengekspor bookmark ke file HTML. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)