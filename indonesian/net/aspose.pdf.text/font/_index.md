---
title: "Kelas Font"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Text.Font. Mewakili objek font"
type: docs
weight: 10690
url: /id/net/aspose.pdf.text/font/
---
## Font class

Mewakili objek font.

```csharp
public sealed class Font
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Mendapatkan nilai BaseFont dari objek font PDF. Juga dikenal sebagai nama PostScript font. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Terkadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font khusus. Nama ini adalah nilai properti font PDF "BaseFont" dan kadang properti ini dapat ditampilkan dalam bentuk heksadesimal. Jika nama ini dibaca langsung, mungkin akan muncul dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, perlu mendekode nama font menurut aturan khusus untuk font tersebut. Properti ini mengembalikan nama font yang telah didekode, jadi gunakanlah untuk kasus ketika Anda menemukan [`FontName`](./fontname/) yang tidak dapat dibaca. Jika properti [`FontName`](./fontname/) memiliki bentuk yang dapat dibaca, properti ini akan sama dengan [`FontName`](./fontname/), sehingga Anda dapat menggunakan properti ini untuk semua kasus ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Mendapatkan nama font dari objek `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Properti berguna untuk menyesuaikan perilaku Font |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Mendapatkan indikasi apakah font tersedia (terpasang) di sistem. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Tujuan metode ini - mengembalikan deskripsi kesalahan jika upaya menyematkan font gagal. Jika tidak ada kasus kesalahan, akan mengembalikan string kosong. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mengukur string. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Menyimpan font ke dalam stream. Perhatikan bahwa font disimpan dalam format TTF menengah yang dimaksudkan hanya untuk digunakan dalam salinan dokumen asli yang telah dikonversi. File font tidak dimaksudkan untuk digunakan di luar konteks dokumen asli. |

## Contoh

Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mengubah font pada kemunculan pencarian pertama.

```csharp
// Buka dokumen
Document doc = new Document(@"D:\Tests\input.pdf");

// Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Terima absorber untuk halaman pertama
doc.Pages[1].Accept(absorber);

// Buat font dan tandai agar disematkan
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Ubah font pada kemunculan teks pertama
absorber.TextFragments[1].TextState.Font = font;


// Simpan dokumen
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


