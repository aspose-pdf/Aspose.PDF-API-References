---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextFragmentState. Mewakili keadaan teks dari sebuah fragmen teks
type: docs
weight: 10970
url: /id/net/aspose.pdf.text/textfragmentstate/
---
## Kelas TextFragmentState

Mewakili keadaan teks dari sebuah fragmen teks.

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
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Mendapatkan atau mengatur jarak karakter dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai default adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dari font lainnya. Dalam hal ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Mendapatkan atau mengatur apakah bendera batas persegi panjang teks digambar. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Mendapatkan atau mengatur font dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Mendapatkan atau mengatur ukuran font dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Mengatur gaya font dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Mendapatkan atau mengatur warna depan dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Mendapatkan atau mengatur opsi pemformatan. Pengaturan opsi akan efektif hanya dalam skenario generator. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal untuk teks. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Mendapatkan atau mengatur skala horizontal dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Mendapatkan atau mengatur ketidakjelasan teks. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Mendapatkan atau mengatur jarak baris dari teks. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Mendapatkan atau mengatur mode rendering dari teks. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Mendapatkan atau mengatur garis coret untuk teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Mendapatkan atau mengatur warna operasi penebalan dari rendering [`TextFragment`](../textfragment/) (teks tebal, batas persegi panjang) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Mendapatkan atau mengatur subskrip dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Mendapatkan atau mengatur superskrip dari teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Mendapatkan tabstop untuk teks. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Mendapatkan atau mengatur garis bawah untuk teks, yang diwakili oleh objek [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Mendapatkan atau mengatur jarak kata dari teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Menerapkan pengaturan dari textState lain. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Memeriksa apakah string input dapat ditempatkan di dalam persegi panjang yang ditentukan. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mengukur tinggi karakter. (2 metode) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mengukur string. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Nilai default dari tabulasi dalam lebar karakter spasi dari font default. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Anda dapat menempatkan tag ini dalam teks untuk menyatakan tabulasi. |

## Catatan

Memberikan cara untuk mengubah properti berikut dari teks: font ([`Font`](./font/) properti) ukuran font ([`FontSize`](./fontsize/) properti) gaya font ([`FontStyle`](./fontstyle/) properti) warna depan ([`ForegroundColor`](./foregroundcolor/) properti) warna latar belakang ([`BackgroundColor`](./backgroundcolor/) properti) Perhatikan bahwa mengubah properti `TextFragmentState` dapat mengubah koleksi [`Segments`](../textfragment/segments/) internal karena TextFragment adalah objek agregat dan dapat mengatur ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah untuk membiarkan koleksi [`Segments`](../textfragment/segments/) tidak berubah, silakan ubah segmen internal secara individu.

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font dari teks dengan objek [`TextState`](../textstate/) .

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../textfragmentabsorber/)
* kelas [Document](../../aspose.pdf/document/)
* kelas [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)