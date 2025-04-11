---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.RedactionAnnotation. Mewakili anotasi Redact
type: docs
weight: 2400
url: /id/net/aspose.pdf.annotations/redactionannotation/
---
## Kelas RedactionAnnotation

Mewakili anotasi Redact.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Dokumen) | Konstruktor untuk RedactionAnnotation. Untuk digunakan dalam Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Halaman, Rectangle) | Konstruktor untuk RedactAnnotation. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar tindakan anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau menetapkan keadaan penampilan anotasi saat ini. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau menetapkan karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Mendapatkan atau menetapkan warna batas yang digambar ketika redaksi tidak aktif. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau menetapkan warna anotasi. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau menetapkan teks anotasi. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Mendapatkan tanggal dan waktu ketika anotasi dibuat. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Mendapatkan atau menetapkan string penampilan default yang akan digunakan dalam memformat teks. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Mendapatkan atau menetapkan warna untuk mengisi anotasi. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Bendera anotasi. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Mendapatkan atau menetapkan ukuran font untuk OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau menetapkan tinggi anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau menetapkan hyperlink fragmen (untuk generator pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Referensi ke anotasi yang "dijawab" oleh anotasi ini. Kedua anotasi harus berada di halaman yang sama dari dokumen. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau menetapkan apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau menetapkan margin luar untuk paragraf (untuk generasi pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau menetapkan tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau menetapkan nama anotasi di halaman. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Mendapatkan atau menetapkan nilai opasitas konstan yang akan digunakan dalam melukis anotasi. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Mendapatkan atau menetapkan teks untuk dicetak pada anotasi redaksi. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi anotasi. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Sebuah array angka 8xN yang menentukan koordinat wilayah konten yang dimaksudkan untuk dihapus. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau menetapkan persegi panjang anotasi. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Jika true, teks overlay akan diulang pada anotasi. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Sebuah string yang menentukan hubungan (jenis "balasan") antara anotasi ini dan satu yang ditentukan oleh InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Mendapatkan atau menetapkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus penampilan anotasi. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Mendapatkan teks yang mewakili deskripsi objek. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Mendapatkan atau menetapkan. Penjajaran Teks Overlay. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau menetapkan penjajaran teks untuk anotasi. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Mendapatkan atau menetapkan teks yang akan ditampilkan di bilah judul anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau menetapkan penjajaran vertikal paragraf |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau menetapkan lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau menetapkan nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Menerima objek pengunjung untuk memproses anotasi. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan penampilan, sesuai dengan transformasi matriks. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Menghapus status dan model status untuk anotasi. Misalnya, menghapus status tinjauan untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Meratakan anotasi yaitu menghapus anotasi dan menambahkannya |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Mendapatkan status anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Mendapatkan model status anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Meratakan anotasi dan meredaksi konten halaman (yaitu menghapus teks dan gambar di bawah anotasi yang direduksi) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Menetapkan status Ditandai dan Tidak Ditandai untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Menetapkan status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Status ditetapkan oleh pengguna yang membuat anotasi target. Nilai diambil dari properti Judul anotasi target. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Menetapkan status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |

### Lihat Juga

* kelas [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)