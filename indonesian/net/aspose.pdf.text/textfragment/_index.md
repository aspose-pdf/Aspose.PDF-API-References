---
title: "Kelas TextFragment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.TextFragment. Mewakili fragmen teks Pdf"
type: docs
weight: 11120
url: /id/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Mewakili fragmen teks Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Menginisialisasi instance baru dari objek `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Membuat objek `TextFragment` dengan satu objek [`TextSegment`](../textsegment/) di dalamnya. Menentukan string teks di dalam segmen. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Menginisialisasi instance baru dari objek `TextFragment` dengan posisi [`TabStops`](../tabstops/) yang telah ditentukan. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Membuat objek `TextFragment` dengan satu objek [`TextSegment`](../textsegment/) di dalamnya dan posisi [`TabStops`](../tabstops/) yang telah ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek `TextFragment`. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Mendapatkan atau mengatur catatan akhir paragraf. (hanya untuk pembuatan pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Mendapatkan atau mengatur catatan kaki paragraf. (hanya untuk pembuatan pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Mendapatkan objek form yang berisi TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur perataan horizontal fragmen teks. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Mengatur hyperlink fragmen |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. (untuk pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Mendapatkan atau mengatur paragraf menjadi inline. Defaultnya false. (untuk pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. (untuk pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. (untuk pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Mendapatkan halaman yang berisi TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Mendapatkan atau mengatur posisi teks untuk teks, yang direpresentasikan dengan objek `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Mendapatkan persegi panjang dari TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Mendapatkan segmen teks untuk `TextFragment` saat ini. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Mendapatkan atau mengatur objek teks String yang direpresentasikan oleh objek `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Mendapatkan atau mengatur keadaan teks untuk teks yang direpresentasikan oleh objek `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Mendapatkan atau mengatur perataan vertikal fragmen teks. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Mendapatkan atau mengatur jumlah baris pembungkus untuk paragraf ini (hanya untuk pembuatan pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Mendapatkan atau mengatur nilai integer yang menunjukkan urutan Z grafik. Grafik dengan ZIndex lebih besar akan ditempatkan di atas grafik dengan ZIndex lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Menggandakan fragmen. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Menggandakan fragmen beserta semua segmen. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Mendapatkan [`TextSegment`](../textsegment/)(s) yang merepresentasikan bagian tertentu dari teks `TextFragment`. |

## Catatan

Dalam beberapa kata, objek `TextFragment` berisi daftar objek [`TextSegment`](../textsegment/). Secara rinci: Teks dokumen pdf dalam Pdf direpresentasikan oleh dua objek dasar: `TextFragment` dan [`TextSegment`](../textsegment/). Perbedaan di antara keduanya sebagian besar bergantung pada konteks. Mari pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk dioperasikan, mengubah propertinya, melihat dll.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek `TextFragment` menyediakan satu set operasi logika atas kumpulan objek fisik [`TextSegment`](../textsegment/) yang mewakili kueri pengguna. Dalam skenario pencarian teks, `TextFragment` adalah representasi logis teks "hello world", dan koleksi objek [`TextSegment`](../textsegment/) mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, `TextFragment` mendekati representasi teks logis. Dan [`TextSegment`](../textsegment/) mendekati representasi teks fisik. Jelas setiap objek [`TextSegment`](../textsegment/) dapat memiliki font, warna, properti posisi masing‑masing. `TextFragment` menyediakan cara sederhana untuk mengubah teks beserta propertinya: mengatur font, ukuran font, warna font, dll. Sementara objek [`TextSegment`](../textsegment/) dapat diakses dan pengguna dapat mengoperasikan objek [`TextSegment`](../textsegment/) secara independen. Perlu dicatat bahwa mengubah properti TextFragment dapat mengubah koleksi dalam [`Segments`](./segments/) karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi [`Segments`](./segments/) tetap tidak berubah, silakan ubah segmen internal satu per satu.

## Contoh

Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Temukan font yang akan digunakan untuk mengubah font teks dokumen
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Ubah teks dan font pada kemunculan teks pertama
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf");  
```

### Lihat Juga

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


