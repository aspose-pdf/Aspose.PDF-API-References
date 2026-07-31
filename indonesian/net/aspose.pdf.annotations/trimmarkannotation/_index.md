---
title: "Kelas TrimMarkAnnotation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Annotations.TrimMarkAnnotation. Mewakili anotasi Trim Mark"
type: docs
weight: 2790
url: /id/net/aspose.pdf.annotations/trimmarkannotation/
---
## TrimMarkAnnotation class

Mewakili anotasi Trim Mark.

```csharp
public sealed class TrimMarkAnnotation : CornerPrinterMarkAnnotation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TrimMarkAnnotation](trimmarkannotation/)(Page, PrinterMarkCornerPosition) | Menginisialisasi instance baru dari kelas `TrimMarkAnnotation`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Mendapatkan daftar aksi anotasi. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mendapatkan atau mengatur status tampilan annotation saat ini. |
| override [AnnotationType](../../aspose.pdf.annotations/trimmarkannotation/annotationtype/) { get; } | Mendapatkan tipe annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Mendapatkan kamus penampilan dari annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Mendapatkan atau mengatur karakteristik batas anotasi. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Mendapatkan karakteristik annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Mendapatkan atau mengatur warna annotation. |
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
| [Position](../../aspose.pdf.annotations/cornerprintermarkannotation/position/) { get; set; } | Mendapatkan atau mengatur posisi tanda pada halaman. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Mendapatkan atau mengatur persegi panjang anotasi. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Mendapatkan kamus tampilan anotasi. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Mendapatkan atau mengatur lebar anotasi. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/trimmarkannotation/accept/)(AnnotationSelector) | Menerima pengunjung untuk pemrosesan anotasi. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Mengkloning instance ini. Metode virtual. Selalu mengembalikan null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Menempatkan konten anotasi langsung pada halaman, objek anotasi akan dihapus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |

## Catatan

Trim mark ditempatkan di sudut-sudut halaman cetak untuk menunjukkan dimana halaman harus dipotong.

### Lihat Juga

* class [CornerPrinterMarkAnnotation](../cornerprintermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


