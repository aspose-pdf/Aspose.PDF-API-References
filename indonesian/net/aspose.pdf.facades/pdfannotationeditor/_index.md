---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfAnnotationEditor. Mewakili kelas untuk bekerja dengan komentar anotasi dokumen PDF
type: docs
weight: 4410
url: /id/net/aspose.pdf.facades/pdfannotationeditor/
---
## Kelas PdfAnnotationEditor

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Menghapus Aspose.Pdf.Document yang terikat dengan facade. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Menghapus anotasi dengan nama anotasi yang ditentukan. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Menghapus semua anotasi dalam dokumen. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Menghapus semua anotasi dari jenis yang ditentukan dalam dokumen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Mengekspor anotasi ke stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Mengekspor konten dari jenis anotasi yang ditentukan ke dalam XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Mengekspor konten dari jenis anotasi yang ditentukan ke dalam XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Mendapatkan daftar anotasi dari jenis yang ditentukan. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Mendapatkan daftar anotasi dari jenis yang ditentukan. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Meratakan semua anotasi dalam dokumen. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Meratakan semua anotasi dalam dokumen. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Meratakan anotasi dari jenis yang ditentukan. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Mengimpor anotasi yang ditentukan dari stream data XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Mengimpor anotasi yang ditentukan dari file XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Mengimpor anotasi ke dalam dokumen dari array stream dokumen PDF lainnya. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Mengimpor anotasi ke dalam dokumen dari array dokumen PDF lainnya. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array stream dokumen PDF lainnya. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array dokumen PDF lainnya. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Mengimpor semua anotasi dari file FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Mengimpor semua anotasi dari stream data XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Mengimpor semua anotasi dari file XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Memodifikasi anotasi dari jenis yang ditentukan pada rentang halaman yang ditentukan. Ini mendukung untuk memodifikasi properti anotasi berikut: Modified, Title, Contents, Color, Subject dan Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Memodifikasi penulis anotasi pada rentang halaman yang ditentukan. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Menghapus area pada halaman yang ditentukan. Semua konten dihapus. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke stream yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)