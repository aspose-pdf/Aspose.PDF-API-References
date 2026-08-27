---
title: "Kelas RenderingOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.RenderingOptions. Mewakili opsi rendering"
type: docs
weight: 9910
url: /id/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

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
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui !:FontRepository.Sources. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Mendapatkan atau mengatur mode optimisasi barcode. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Menunjukkan bahwa semua font akan dikonversi ke versi unicode TTF. Hal ini berguna untuk alasan kompatibilitas dan mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, melainkan hanya simbol yang digunakan dalam teks. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan ketidakhadiran font akan diabaikan. true - berarti bahwa kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false secara default |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Jumlah maksimum font dalam cache font. Nilai default adalah 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Mendapatkan atau mengatur mode optimasi dimensi. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Mendapatkan atau mengatur mode di mana font sistem dirender secara native. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Penggunaan flag ini mengaktifkan mekanisme font hinting. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus mengaktifkan flag ini dapat menyelesaikan masalah keterbacaan teks. Saat ini penggunaan flag ini hanya berpengaruh pada font TTF, jika font tersebut digunakan dalam dokumen sumber. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


