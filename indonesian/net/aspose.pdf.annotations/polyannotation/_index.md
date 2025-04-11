---
title: Class PolyAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.PolyAnnotation. Kelas dasar abstrak untuk anotasi poligon
type: docs
weight: 2290
url: /id/net/aspose.pdf.annotations/polyannotation/
---
## Kelas PolyAnnotation

Kelas dasar abstrak untuk anotasi poligon.

```csharp
public abstract class PolyAnnotation : MarkupAnnotation
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar tindakan anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau menetapkan keadaan penampilan anotasi saat ini. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan dari anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau menetapkan karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau menetapkan warna anotasi. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau menetapkan teks anotasi. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Mendapatkan tanggal dan waktu ketika anotasi dibuat. |
| [EndingStyle](../../aspose.pdf.annotations/polyannotation/endingstyle/) { get; set; } | Mendapatkan atau menetapkan gaya akhir garis kedua. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Bendera dari anotasi. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau menetapkan tinggi anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau menetapkan hyperlink fragmen (untuk generator pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Referensi ke anotasi yang "dibalas" oleh anotasi ini. Kedua anotasi harus berada di halaman yang sama dari dokumen. |
| [Intent](../../aspose.pdf.annotations/polyannotation/intent/) { get; set; } | Mendapatkan atau menetapkan niat dari anotasi poligon atau polilin. |
| [InteriorColor](../../aspose.pdf.annotations/polyannotation/interiorcolor/) { get; set; } | Mendapatkan atau menetapkan warna interior yang digunakan untuk mengisi akhir garis anotasi. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau menetapkan apakah paragraf adalah inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau menetapkan margin luar untuk paragraf (untuk generasi pdf) |
| [Measure](../../aspose.pdf.annotations/polyannotation/measure/) { get; set; } | Satuan ukuran yang ditentukan untuk anotasi ini. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau menetapkan tanggal dan waktu ketika anotasi terakhir kali dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau menetapkan nama anotasi di halaman. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Mendapatkan atau menetapkan nilai opasitas konstan yang akan digunakan dalam menggambar anotasi. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi anotasi. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau menetapkan persegi panjang anotasi. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Sebuah string yang menentukan hubungan (jenis "balasan") antara anotasi ini dan satu yang ditentukan oleh InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Mendapatkan atau menetapkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [StartingStyle](../../aspose.pdf.annotations/polyannotation/startingstyle/) { get; set; } | Mendapatkan atau menetapkan gaya akhir garis pertama. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus penampilan dari anotasi. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Mendapatkan teks yang mewakili deskripsi objek. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan teks untuk anotasi. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Mendapatkan atau menetapkan teks yang akan ditampilkan di bilah judul anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan vertikal paragraf |
| [Vertices](../../aspose.pdf.annotations/polyannotation/vertices/) { get; set; } | Mendapatkan atau menetapkan array titik yang mewakili koordinat horizontal dan vertikal dari setiap titik sudut. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau menetapkan lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau menetapkan nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | Menerima pengunjung untuk pemrosesan anotasi. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/polyannotation/changeafterresize/)(Matrix) | Memperbarui titik-titik di Vertices, sesuai dengan transformasi matriks. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Menghapus status dan model status untuk anotasi. Misalnya, menghapus status tinjauan untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Menempatkan konten anotasi langsung di halaman, objek anotasi akan dihapus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Mendapatkan status dari anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Mendapatkan model status dari anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Menetapkan status Ditandai dan Tidak Ditandai untuk anotasi. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Menetapkan status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Status ditetapkan oleh pengguna yang membuat anotasi target. Nilai diambil dari properti Title dari anotasi target. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Menetapkan status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci status dan modelstatus. |

### Lihat Juga

* kelas [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)