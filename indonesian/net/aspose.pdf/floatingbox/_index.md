---
title: "Kelas FloatingBox"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.FloatingBox."
type: docs
weight: 4990
url: /id/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Menginisialisasi sebuah instance baru dari kelas `FloatingBox` dengan lebar dan tinggi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur objek [`Color`](../color/) yang menunjukkan warna latar belakang kotak mengambang. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Mendapatkan atau mengatur objek [`BorderInfo`](../borderinfo/) yang menunjukkan informasi batas kotak mengambang. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Mendapatkan atau mengatur informasi kolom |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Mendapatkan atau mengatur nilai float yang menunjukkan tinggi kotak mengambang. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf perlu diulang pada halaman berikutnya. Nilai default adalah false. Atribut ini hanya valid ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Mendapatkan atau mengatur koordinat kiri tabel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Mendapatkan atau mengatur objek [`MarginInfo`](../margininfo/) yang menunjukkan padding kotak mengambang. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Mendapatkan atau mengatur koleksi [`Paragraphs`](./paragraphs/) yang menunjukkan semua paragraf dalam sel. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Menentukan varian untuk menentukan lokasi FloatingBox pada halaman. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Mendapatkan atau mengatur koordinat atas tabel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Mendapatkan atau mengatur nilai float yang menunjukkan lebar kotak mengambang. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Menggandakan objek `FloatingBox` baru. Paragraf dalam kotak mengambang tidak digandakan. |

### Lihat Juga

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


