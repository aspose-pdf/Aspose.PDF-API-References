---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Text.Font. Mewakili objek font
type: docs
weight: 10510
url: /id/net/aspose.pdf.text/font/
---
## Kelas Font

Mewakili objek font.

```csharp
public sealed class Font
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Mendapatkan nilai BaseFont dari objek font PDF. Juga dikenal sebagai nama PostScript dari font. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Terkadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font yang spesifik. Nama ini adalah nilai dari properti font PDF "BaseFont" dan terkadang properti ini dapat direpresentasikan dalam bentuk heksadesimal. Jika membaca nama ini secara langsung, itu dapat direpresentasikan dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, perlu untuk mendekode nama font dengan aturan yang spesifik untuk font ini. Properti ini mengembalikan nama font yang telah didekode, jadi gunakan ini untuk kasus ketika Anda menemui [`FontName`](./fontname/) yang tidak dapat dibaca. Jika properti [`FontName`](./fontname/) memiliki bentuk yang dapat dibaca, properti ini akan sama dengan [`FontName`](./fontname/), jadi Anda dapat menggunakan properti ini untuk semua kasus ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Mendapatkan nama font dari objek `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Properti berguna untuk mengatur perilaku Font |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Mendapatkan indikasi apakah font ada (terinstal) di sistem. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font disematkan. Font yang berbasis IFont akan secara otomatis menjadi subset dan disematkan |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah font adalah subset. Font yang berbasis IFont akan secara otomatis menjadi subset dan disematkan |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Tujuan dari metode ini - untuk mengembalikan deskripsi kesalahan jika upaya untuk menyematkan font gagal. Jika tidak ada kasus kesalahan, itu mengembalikan string kosong. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mengukur string. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Menyimpan font ke dalam stream. Perhatikan bahwa font disimpan dalam format TTF sementara yang dimaksudkan untuk digunakan dalam salinan yang dikonversi dari dokumen asli saja. File font tidak dimaksudkan untuk digunakan di luar konteks dokumen asli. |

## Contoh

Contoh ini menunjukkan bagaimana cara mencari teks di halaman pertama dan mengubah font dari kemunculan pencarian pertama.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Lihat Juga

* kelas [TextFragmentAbsorber](../textfragmentabsorber/)
* kelas [FontRepository](../fontrepository/)
* kelas [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)