---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextState. Mewakili keadaan teks dari sebuah teks
type: docs
weight: 11070
url: /id/net/aspose.pdf.text/textstate/
---
## Kelas TextState

Mewakili keadaan teks dari sebuah teks

```csharp
public class TextState
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextState](textstate/#constructor)() | Membuat objek keadaan teks. |
| [TextState](textstate/#constructor_2)(Color) | Membuat objek keadaan teks dengan spesifikasi warna latar depan. |
| [TextState](textstate/#constructor_1)(double) | Membuat objek keadaan teks dengan spesifikasi ukuran font. |
| [TextState](textstate/#constructor_4)(string) | Membuat objek keadaan teks dengan spesifikasi keluarga font. |
| [TextState](textstate/#constructor_3)(Color, double) | Membuat objek keadaan teks dengan spesifikasi warna latar depan dan ukuran font. |
| [TextState](textstate/#constructor_6)(string, double) | Membuat objek keadaan teks dengan spesifikasi keluarga font dan ukuran font. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Membuat objek keadaan teks dengan spesifikasi keluarga font dan gaya font. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Mengatur warna latar belakang teks. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Mendapatkan atau mengatur jarak karakter dari teks. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai default adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi daripada font lainnya. Dalam hal ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Mendapatkan atau mengatur font dari teks. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Mendapatkan atau mengatur ukuran font dari teks. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Mengatur gaya font dari teks. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar depan dari teks. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal untuk teks. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Mendapatkan atau mengatur skala horizontal dari teks. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Mendapatkan atau mengatur ketidaknampakan teks. Ini pada dasarnya mencerminkan status [`RenderingMode`](./renderingmode/), kecuali untuk beberapa kasus khusus (seperti pemotongan). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Mendapatkan atau mengatur jarak baris dari teks. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Mendapatkan atau mengatur mode rendering teks. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Mendapatkan atau mengatur coretan untuk teks, yang diwakili oleh objek [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Mendapatkan atau mengatur warna latar depan dari teks. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Mendapatkan atau mengatur subskrip dari teks. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Mendapatkan atau mengatur superskrip dari teks. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Mendapatkan atau mengatur garis bawah untuk teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Mendapatkan atau mengatur jarak kata dari teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Menerapkan pengaturan dari textState lain. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mengukur tinggi karakter. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mengukur string. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Nilai default dari tabulasi dalam lebar karakter spasi dari font default. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Anda dapat menempatkan tag ini dalam teks untuk menyatakan tabulasi. |

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)