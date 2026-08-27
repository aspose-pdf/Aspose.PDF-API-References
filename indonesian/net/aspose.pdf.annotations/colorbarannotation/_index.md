---
title: "Kelas ColorBarAnnotation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Annotations.ColorBarAnnotation kelas. Kelas yang merepresentasikan anotasi ColorBarAnnotation. Properti Color diabaikan dan diganti dengan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi anotasi secara horizontal atau vertikal. Selanjutnya diperiksa apakah persegi panjang anotasi berada di luar TrimBox dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar dan tinggi agar anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol; dalam kasus ini anotasi tetap ada pada halaman tetapi tidak ditampilkan."
type: docs
weight: 1690
url: /id/net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

Kelas yang merepresentasikan anotasi ColorBarAnnotation. Properti Color diabaikan, sebagai gantinya digunakan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa apakah persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam kasus ini, anotasi tetap ada di halaman, tetapi tidak ditampilkan).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | Membuat anotasi ColorBar baru pada halaman yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar aksi anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau mengatur status tampilan annotation saat ini. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Mendapatkan tipe annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan dari annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna annotation. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Mendapatkan atau mengatur warna (salah satu cyan, magenta, yellow, black) untuk anotasi yang digambar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Mendapatkan atau mengatur teks annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Mendapatkan nama lengkap yang memenuhi syarat dari annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Mendapatkan atau mengatur tinggi annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi baru-baru ini dimodifikasi. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Mendapatkan atau mengatur nama anotasi pada halaman. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Mendapatkan indeks halaman yang berisi anotasi. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang anotasi. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus tampilan anotasi. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Menerima objek visitor untuk memproses anotasi. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Perbarui parameter dan tampilan, sesuai dengan transformasi matriks dan pemindahan di luar TrimBox jika diperlukan. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Menempatkan konten anotasi langsung pada halaman, objek anotasi akan dihapus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |

### Lihat Juga

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


