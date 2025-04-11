---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.RenderingOptions. Mewakili opsi rendering
type: docs
weight: 9760
url: /id/net/aspose.pdf/renderingoptions/
---
## Kelas RenderingOptions

Mewakili opsi rendering.

```csharp
public sealed class RenderingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma penggantian font mengikuti langkah-langkah ini: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditentukan oleh pengguna, cari melalui font yang ditambahkan melalui !:FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font sesuai. Cobalah untuk menemukan dan menggunakan font ini dari sistem. 4. Sebagai cadangan, cari sistem untuk font yang mampu menampilkan karakter yang diperlukan. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Mendapatkan atau mengatur mode optimasi barcode. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Menunjukkan bahwa semua font akan dikonversi ke versi TTF unicode. Itu berguna untuk alasan kompatibilitas dan untuk mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, tetapi hanya simbol yang digunakan dalam teks. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Mendapatkan atau mengatur nilai yang digunakan untuk meningkatkan atau mengurangi lebar persegi panjang untuk operator AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti bahwa kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak benar akan dilewati selama pemrosesan. false secara default |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Jumlah maksimum font dalam cache font. Nilai default adalah 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Mendapatkan atau mengatur mode optimasi dimensi. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Mendapatkan atau mengatur mode di mana font sistem dirender secara native. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Penggunaan flag ini mengaktifkan mekanisme hinting font. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus, mengaktifkan flag ini dapat menyelesaikan masalah dengan keterbacaan teks. Saat ini, penggunaan flag ini hanya dapat memberikan efek untuk font TTF, jika font ini digunakan dalam dokumen sumber. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Mendapatkan atau mengatur nilai yang digunakan untuk meningkatkan atau mengurangi lebar persegi panjang untuk operator AppendRectangle. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)