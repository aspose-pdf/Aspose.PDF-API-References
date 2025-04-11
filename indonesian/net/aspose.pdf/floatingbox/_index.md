---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /id/net/aspose.pdf/floatingbox/
---
## Kelas FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Menginisialisasi instance baru dari kelas `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Menginisialisasi instance baru dari kelas `FloatingBox` dengan lebar dan tinggi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Mendapatkan atau menetapkan objek [`Color`](../color/) yang menunjukkan warna latar belakang dari kotak mengambang. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Mendapatkan atau menetapkan gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Mendapatkan atau menetapkan objek [`BorderInfo`](../borderinfo/) yang menunjukkan informasi batas dari kotak mengambang. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Mendapatkan atau menetapkan informasi kolom |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Mendapatkan atau menetapkan nilai float yang menunjukkan tinggi dari kotak mengambang. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan horizontal dari paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau menetapkan hyperlink fragmen (untuk generator pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau menetapkan paragraf sebagai inline. Default adalah false. (untuk generasi pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang memaksa paragraf ini dihasilkan di halaman baru. Default adalah false. (untuk generasi pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf saat ini tetap di halaman yang sama bersama dengan paragraf berikutnya. Default adalah false. (untuk generasi pdf) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Mendapatkan atau menetapkan nilai bool yang menunjukkan apakah paragraf perlu diulang di halaman berikutnya. Nilai default adalah false. Atribut ini hanya berlaku ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Mendapatkan atau menetapkan koordinat kiri tabel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau menetapkan margin luar untuk paragraf (untuk generasi pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Mendapatkan atau menetapkan objek [`MarginInfo`](../margininfo/) yang menunjukkan padding dari kotak mengambang. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Mendapatkan atau menetapkan koleksi [`Paragraphs`](./paragraphs/) yang menunjukkan semua paragraf dalam sel. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Menentukan varian untuk menentukan lokasi FloatingBox di halaman. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Mendapatkan atau menetapkan koordinat atas tabel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau menetapkan perataan vertikal dari paragraf |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Mendapatkan atau menetapkan nilai float yang menunjukkan lebar dari kotak mengambang. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau menetapkan nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Mengkloning objek `FloatingBox` baru. Paragraf dalam kotak mengambang tidak dikloning. |

### Lihat Juga

* kelas [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)