---
title: "Kelas TextSegment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextSegment. Mewakili segmen teks Pdf"
type: docs
weight: 11240
url: /id/net/aspose.pdf.text/textsegment/
---
## TextSegment class

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
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek `TextSegment`. YIndent dari struktur Position mewakili koordinat baseline dari segmen teks. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Mendapatkan koleksi objek CharInfo yang mewakili informasi tentang karakter dalam segmen teks. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Mendapatkan indeks karakter akhir dari segmen saat ini dalam operator tampilkan teks (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Mendapatkan atau mengatur hyperlink segmen (untuk pembuat pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextSegment. |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Mendapatkan indeks karakter awal dari segmen saat ini dalam operator tampilkan teks (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Mendapatkan atau mengatur objek teks String yang direpresentasikan oleh objek `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Mendapatkan atau mengatur keadaan teks untuk teks yang direpresentasikan oleh objek `TextSegment`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Menyandikan string sebagai html. |

## Catatan

Dalam beberapa kata, objek `TextSegment` adalah anak dari objek [`TextFragment`](../textfragment/). Secara detail: Teks dokumen pdf dalam Pdf direpresentasikan oleh dua objek dasar: [`TextFragment`](../textfragment/) dan `TextSegment`. Perbedaan di antara keduanya sebagian besar bergantung pada konteks. Mari pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk dioperasikan, mengubah propertinya, melihat dll.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek [`TextFragment`](../textfragment/) menyediakan satu set operasi logika atas kumpulan objek `TextSegment` fisik yang mewakili kueri pengguna. Dalam skenario pencarian teks, [`TextFragment`](../textfragment/) adalah representasi logis teks "hello world", dan koleksi objek `TextSegment` mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, [`TextFragment`](../textfragment/) mendekati representasi teks logis. Dan `TextSegment` mendekati representasi teks fisik. Jelas setiap objek `TextSegment` dapat memiliki font, warna, properti posisi masing‑masing. [`TextFragment`](../textfragment/) menyediakan cara sederhana untuk mengubah teks beserta propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara objek `TextSegment` dapat diakses dan pengguna dapat mengoperasikan objek `TextSegment` secara independen.

## Contoh

Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks menggunakan objek [`TextState`](./textstate/) dari objek `TextSegment`.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah warna latar depan segmen teks pertama dari kemunculan teks pertama
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Ubah ukuran font segmen teks pertama dari kemunculan teks pertama
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


