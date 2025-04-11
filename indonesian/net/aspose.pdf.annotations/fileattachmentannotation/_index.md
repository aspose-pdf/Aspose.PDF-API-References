---
title: Class FileAttachmentAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.FileAttachmentAnnotation. Kelas ini menggambarkan anotasi lampiran file
type: docs
weight: 1710
url: /id/net/aspose.pdf.annotations/fileattachmentannotation/
---
## Kelas FileAttachmentAnnotation

Kelas ini menggambarkan anotasi lampiran file.

```csharp
public sealed class FileAttachmentAnnotation : MarkupAnnotation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileAttachmentAnnotation](fileattachmentannotation/)(Halaman, Rectangle, FileSpecification) | Membuat anotasi FileAttachment baru pada halaman yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar tindakan anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau mengatur keadaan penampilan anotasi saat ini. |
| override [AnnotationType](../../aspose.pdf.annotations/fileattachmentannotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan dari anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna anotasi. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau mengatur teks anotasi. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Mendapatkan tanggal dan waktu ketika anotasi dibuat. |
| [File](../../aspose.pdf.annotations/fileattachmentannotation/file/) { get; set; } | Spesifikasi file yang terkait dengan anotasi ini. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Bendera dari anotasi. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau mengatur tinggi anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [Icon](../../aspose.pdf.annotations/fileattachmentannotation/icon/) { get; set; } | Mendapatkan atau mengatur ikon yang akan digunakan dalam menampilkan anotasi. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Referensi ke anotasi yang "dibalas" oleh anotasi ini. Kedua anotasi harus berada di halaman yang sama dari dokumen. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau mengatur nama anotasi di halaman. |
| [Opacity](../../aspose.pdf.annotations/fileattachmentannotation/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas ikon dari 0 hingga 1: 0 - sepenuhnya transparan, 1 - sepenuhnya tidak transparan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi anotasi. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang anotasi. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Sebuah string yang menentukan hubungan (jenis "balasan") antara anotasi ini dan satu yang ditentukan oleh InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Mendapatkan atau mengatur string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus penampilan dari anotasi. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Mendapatkan teks yang mewakili deskripsi objek. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Mendapatkan atau mengatur teks yang akan ditampilkan di bilah judul anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/fileattachmentannotation/accept/)(AnnotationSelector) | Menerima objek pengunjung untuk memproses anotasi. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan penampilan, sesuai dengan transformasi matriks. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Menghapus status dan model status untuk anotasi. Misalnya, menghapus status tinjauan untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Menempatkan konten anotasi langsung di halaman, objek anotasi akan dihapus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Mendapatkan status anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Mendapatkan model status dari anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Mengatur status Ditandai dan Tidak Ditandai untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Mengatur status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Status diatur oleh pengguna yang membuat anotasi target. Nilai diambil dari properti Title dari anotasi target. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Mengatur status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |

### Lihat Juga

* kelas [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)