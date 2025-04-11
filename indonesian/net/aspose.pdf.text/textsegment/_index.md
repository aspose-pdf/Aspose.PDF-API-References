---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.TextSegment. Mewakili segmen teks Pdf
type: docs
weight: 11050
url: /id/net/aspose.pdf.text/textsegment/
---
## Kelas TextSegment

Mewakili segmen teks Pdf.

```csharp
public sealed class TextSegment
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Membuat objek TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Membuat objek TextSegment. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang diwakili dengan objek `TextSegment`. YIndent dari struktur Position mewakili koordinat baseline dari segmen teks. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Mendapatkan koleksi objek CharInfo yang mewakili informasi tentang karakter dalam segmen teks. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Mendapatkan indeks karakter akhir dari segmen saat ini dalam operator teks tampil (Tj, TJ) segmen. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink segmen (untuk generator pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Mendapatkan posisi teks untuk teks, yang diwakili dengan objek `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Mendapatkan indeks karakter awal dari segmen saat ini dalam operator teks tampil (Tj, TJ) segmen. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Mendapatkan atau mengatur objek teks String yang diwakili oleh objek `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi edit teks. Opsi ini mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Mendapatkan atau mengatur status teks untuk teks yang diwakili oleh objek `TextSegment`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Mengkodekan string sebagai html. |

## Catatan

Dalam beberapa kata, objek `TextSegment` adalah anak dari objek [`TextFragment`](../textfragment/). Secara rinci: Teks dokumen pdf dalam Pdf diwakili oleh dua objek dasar: [`TextFragment`](../textfragment/) dan `TextSegment`. Perbedaan antara keduanya sebagian besar tergantung pada konteks. Mari kita pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk beroperasi dengannya, mengubah propertinya, melihat, dll.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Representasi teks pdf secara fisik sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek [`TextFragment`](../textfragment/) menyediakan satu set operasi logis tunggal di atas set objek fisik `TextSegment` yang mewakili kueri pengguna. Dalam skenario pencarian teks, [`TextFragment`](../textfragment/) adalah representasi logis teks "hello world", dan koleksi objek `TextSegment` mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, [`TextFragment`](../textfragment/) dekat dengan representasi teks logis. Dan `TextSegment` dekat dengan representasi teks fisik. Jelas setiap objek `TextSegment` dapat memiliki font, warna, dan properti posisi sendiri. [`TextFragment`](../textfragment/) menyediakan cara sederhana untuk mengubah teks dengan propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara itu, objek `TextSegment` dapat diakses dan pengguna dapat beroperasi dengan objek `TextSegment` secara independen.

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font dari teks dengan objek [`TextState`](./textstate/) dari objek `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)