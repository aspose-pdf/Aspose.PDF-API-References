---
title: "Kelas PdfAnnotationEditor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor class. Mewakili kelas untuk bekerja dengan komentar anotasi dokumen PDF"
type: docs
weight: 4530
url: /id/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Mewakili kelas untuk bekerja dengan anotasi dokumen PDF (komentar).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Menginisialisasi objek `PdfAnnotationEditor` baru. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Menginisialisasi objek `PdfAnnotationEditor` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Membuang Aspose.Pdf.Document yang terikat dengan sebuah facade. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Menghapus anotasi dengan nama anotasi yang ditentukan. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Menghapus semua anotasi dalam dokumen. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Menghapus semua anotasi dari tipe yang ditentukan dalam dokumen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Mengekspor anotasi ke aliran. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Mengekspor konten dari tipe anotasi yang ditentukan ke XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Mengekspor konten dari tipe anotasi yang ditentukan ke XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Mendapatkan daftar anotasi dari tipe yang ditentukan. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Mendapatkan daftar anotasi dari tipe yang ditentukan. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Menyatukan semua anotasi dalam dokumen. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Menyatukan semua anotasi dalam dokumen. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Menyatukan anotasi dari tipe yang ditentukan. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Mengimpor anotasi yang ditentukan dari aliran data XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Mengimpor anotasi yang ditentukan dari file XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Mengimpor anotasi ke dalam dokumen dari array aliran dokumen PDF lain. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Mengimpor anotasi ke dalam dokumen dari array dokumen PDF lain. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array aliran dokumen PDF lain. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array dokumen PDF lain. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Mengimpor semua anotasi dari file FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Mengimpor semua anotasi dari aliran data XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Mengimpor semua anotasi dari file XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Mengubah anotasi dari tipe yang ditentukan pada rentang halaman yang ditentukan. Mendukung pengubahan properti anotasi berikut: Modified, Title, Contents, Color, Subject, dan Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Mengubah penulis anotasi pada rentang halaman yang ditentukan. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Menyensor area pada halaman yang ditentukan. Semua konten dihapus. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


