---
title: "Kelas TextFragmentState"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextFragmentState. Mewakili keadaan teks dari sebuah fragmen teks"
type: docs
weight: 11150
url: /id/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Mewakili status teks dari sebuah fragmen teks.

```csharp
public sealed class TextFragmentState : TextState
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Menginisialisasi instance baru dari objek `TextFragmentState` dengan objek [`TextFragment`](../textfragment/) yang ditentukan. Inisialisasi `TextFragmentState` ini tidak didukung. TextFragmentState hanya tersedia dengan properti [`TextState`](../textfragment/textstate/). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Mengatur warna latar belakang teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Mendapatkan atau mengatur spasi karakter teks, yang diwakili oleh objek [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai default adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi daripada font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Mendapatkan atau mengatur apakah flag gambar batas persegi panjang teks. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Mendapatkan atau mengatur font teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Mendapatkan atau mengatur ukuran font teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Mengatur gaya font teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar depan teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Mendapatkan atau mengatur opsi pemformatan. Penetapan opsi hanya akan efektif dalam skenario generator. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal untuk teks. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Mendapatkan atau mengatur skala horizontal teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Mendapatkan atau mengatur ketidaknampakan teks. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Mendapatkan atau mengatur jarak baris teks. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Mendapatkan atau mengatur mode rendering teks. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Mendapatkan atau mengatur garis coret pada teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Mendapatkan atau mengatur operasi pewarnaan goresan pada rendering [`TextFragment`](../textfragment/) (teks gores, batas persegi panjang). |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Mendapatkan atau mengatur subskrip teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Mendapatkan atau mengatur superskrip teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/). |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Mendapatkan tabstop untuk teks. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Anda dapat menempatkan tag ini dalam teks untuk menyatakan tabulasi. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Mendapatkan atau mengatur garis bawah pada teks, yang direpresentasikan oleh objek [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Mendapatkan atau mengatur spasi kata pada teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Menerapkan pengaturan dari textState lain. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Memeriksa apakah string input dapat ditempatkan di dalam persegi panjang yang didefinisikan. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mengukur tinggi karakter. (2 metode) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mengukur string. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Nilai default tabulasi dalam lebar karakter spasi pada font default. |

## Catatan

Memberikan cara untuk mengubah properti berikut dari teks: font (properti [`Font`](./font/)) ukuran font (properti [`FontSize`](./fontsize/)) gaya font (properti [`FontStyle`](./fontstyle/)) warna latar depan (properti [`ForegroundColor`](./foregroundcolor/)) warna latar belakang (properti [`BackgroundColor`](./backgroundcolor/)) Catatan bahwa mengubah properti `TextFragmentState` dapat mengubah koleksi dalam [`Segments`](../textfragment/segments/) karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi [`Segments`](../textfragment/segments/) tidak berubah, silakan ubah segmen internal satu per satu.

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek [`TextState`](../textstate/).

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah warna latar depan pada kemunculan teks pertama
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ubah ukuran font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.FontSize = 15;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


