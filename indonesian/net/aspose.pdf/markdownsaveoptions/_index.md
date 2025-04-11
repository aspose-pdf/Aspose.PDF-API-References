---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.MarkdownSaveOptions. Mewakili kelas opsi penyimpanan dokumen dalam format markdown
type: docs
weight: 6910
url: /id/net/aspose.pdf/markdownsaveoptions/
---
## Kelas MarkdownSaveOptions

Mewakili kelas opsi penyimpanan dokumen dalam format markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Mendapatkan atau mengatur area persegi panjang untuk mengekstrak konten ke markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glyph font akan disimpan saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Mendapatkan atau mengatur gaya penekanan untuk dokumen yang dihasilkan. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Mendapatkan dan mengatur properti yang menunjukkan apakah grafik vektor harus diekstrak. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Mendefinisikan tingkat heading yang diharapkan untuk digunakan dalam strategi pengenalan header FontSize. Jika nilai properti ini diatur, maka pengenalan header !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic akan dipilih ketika strategi !:PdfToMarkdown.HeadingRecognitionStrategy.Auto diatur bahkan jika dokumen mengandung bookmark. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Mendapatkan atau mengatur strategi pengenalan heading. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Mendapatkan atau mengatur gaya heading untuk dokumen yang dihasilkan. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Mendapatkan atau mengatur gaya pemisahan baris untuk dokumen yang dihasilkan. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Jika nilai tidak ditentukan, maka gambar akan ditulis ke direktori yang sama dengan file markdown itu sendiri. Ini bukan jalur, ini hanya nama! Direktori ini akan secara otomatis dibuat di direktori dengan file markdown yang disimpan. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Mendapatkan dan mengatur izin untuk mengonversi subskrip dan superskrip. Nilai ini adalah true secara default. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Mendapatkan dan mengatur izin untuk menggunakan tag img untuk menyisipkan gambar di sebelah kiri dan kanan teks. Dalam hal ini, di penampil markdown, teks akan membungkus gambar. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Simpan dilanjutkan, namun pengguna juga dapat mengembalikan Menghentikan di mana operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF mengandung gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang diletakkan berdekatan satu sama lain. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) terkadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik mereka dalam penghalusan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan itu. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)