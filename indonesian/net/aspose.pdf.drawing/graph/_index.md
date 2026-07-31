---
title: "Kelas Graph"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Drawing.Graph. Mewakili grafik paragraf generator grafis"
type: docs
weight: 4060
url: /id/net/aspose.pdf.drawing/graph/
---
## Graph class

Mewakili grafik - paragraf generator grafis.

```csharp
public sealed class Graph : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Menginisialisasi instance baru dari kelas `Graph`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Mendapatkan atau mengatur batas. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Mendapatkan atau mengatur objek [`GraphInfo`](./graphinfo/) yang menunjukkan info grafik, seperti warna, lebar garis, dll. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Mendapatkan atau mengatur nilai float yang menunjukkan tinggi grafik. Satuannya adalah point. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal paragraf |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink fragmen (untuk pdf generator). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Mendapatkan atau mengatur perubahan posisi saat ini setelah memproses paragraf. (default true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Mendapatkan atau mengatur koordinat kiri tabel. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Mendapatkan atau mengatur koleksi [`Shapes`](./shapes/) yang menunjukkan semua bentuk dalam grafik. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Mendapatkan atau mengatur nilai string yang menunjukkan judul grafik. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Mendapatkan atau mengatur koordinat atas tabel. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal paragraf. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Mendapatkan atau mengatur nilai float yang menunjukkan lebar grafik. Satuannya adalah point. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Menggandakan grafik. |

### Lihat Juga

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)


