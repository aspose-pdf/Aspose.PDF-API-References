---
title: Class ColorBarAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.ColorBarAnnotation. Kelas yang mewakili anotasi ColorBarAnnotation. Properti Color diabaikan, sebaliknya digunakan warna ColorsOfCMYK. Saat dibuat, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa bahwa persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol.
type: docs
weight: 1600
url: /id/net/aspose.pdf.annotations/colorbarannotation/
---
## Kelas ColorBarAnnotation

Kelas yang mewakili anotasi ColorBarAnnotation. Properti Color diabaikan, sebaliknya digunakan warna ColorsOfCMYK. Saat dibuat, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa bahwa persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam hal ini, anotasi ada di halaman tetapi tidak ditampilkan).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | Membuat anotasi ColorBar baru di halaman yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar tindakan anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau mengatur keadaan penampilan anotasi saat ini. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Mendapatkan jenis anotasi. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan anotasi. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik anotasi. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna anotasi. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Mendapatkan atau mengatur warna (salah satu dari cyan, magenta, kuning, hitam) untuk anotasi yang digambar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau mengatur teks anotasi. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Bendera anotasi. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari anotasi. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau mengatur tinggi anotasi. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf sebagai inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk generasi pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi terakhir kali dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau mengatur nama anotasi di halaman. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi anotasi. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang anotasi. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus penampilan anotasi. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Menerima objek pengunjung untuk memproses anotasi. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Memperbarui parameter dan penampilan, sesuai dengan transformasi matriks dan memindahkan di luar TrimBox jika perlu. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Menempatkan konten anotasi langsung di halaman, objek anotasi akan dihapus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |

### Lihat Juga

* kelas [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)