---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PdfFormatConversionOptions. mewakili sekumpulan opsi untuk mengonversi dokumen PDF
type: docs
weight: 8380
url: /id/net/aspose.pdf/pdfformatconversionoptions/
---
## Kelas PdfFormatConversionOptions

mewakili sekumpulan opsi untuk mengonversi dokumen PDF

```csharp
public class PdfFormatConversionOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktor |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Mendapatkan objek PdfFormatConversionOptions dengan parameter default |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Flag ini mengontrol penyelarasan teks dalam dokumen yang dikonversi. Secara default, konversi dokumen tidak mempengaruhi penyelarasan teks dan membiarkan teks seperti adanya. Namun, dalam beberapa kasus, substitusi font menyebabkan tumpang tindih teks atau ruang ekstra dalam dokumen yang dikonversi. Ketika flag ini diatur, operasi penyelarasan khusus akan dilakukan. Flag ini harus diatur hanya untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau ruang teks ekstra karena penggunaan flag ini mengurangi kinerja dan dalam beberapa kasus dapat merusak konten teks. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Tindakan untuk gambar dengan masker lembut. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Tindakan untuk objek yang tidak dapat dikonversi |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategi untuk mengecualikan font yang berlebihan dan mengurangi ukuran file dokumen. Parameter ini hanya berarti ketika flag [`OptimizeFileSize`](./optimizefilesize/) diatur ke true. Secara default, kombinasi strategi SubsetFonts dan RemoveDuplicatedFonts digunakan. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opsi untuk kasus ketika tidak mungkin untuk menyematkan beberapa font ke dalam dokumen PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Format PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Mendapatkan atau mengatur nama file profil icc. Dalam kasus null, profil icc default digunakan. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Mendapatkan/mengatur jalannya aliran gambar dalam mode asinkron. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Apakah mode konversi memori rendah diaktifkan |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Mendapatkan atau mengatur apakah akan meneruskan data dari Info ke Metadata saat dikonversi ke PDF 2.0. True secara default. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Jalur ke file tempat komentar akan disimpan. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Aliran tempat komentar akan disimpan. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Menyimpan flag untuk mengontrol proses konversi PDF/A untuk kasus ketika dokumen sumber tidak sesuai dengan spesifikasi PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Properti ini adalah properti keluar. Ini menyimpan semua font (nama font) yang tidak ditemukan di komputer pada konversi PDF/A terakhir. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Mendapatkan atau mengatur flag yang mengaktifkan/mematikan mode konversi khusus untuk mendapatkan dokumen PDF/A dengan ukuran file yang lebih kecil. Sekarang flag ini berdampak pada optimasi font yang digunakan dalam dokumen PDF, mungkin, di masa depan, flag ini juga akan digunakan untuk mengaktifkan optimasi untuk struktur data lain, seperti grafik. Set flag ini dan mode dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan mengurangi kinerja konversi. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Mendapatkan atau mengatur [`OutputIntent`](../outputintent/) untuk konversi format PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategi untuk memproses simbol dari area penggunaan pribadi Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategi untuk menyalin data pengkodean untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable pengkodean. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Tindakan untuk objek yang dimasker gambar |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Dapat bernilai null. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategi untuk menyelaraskan teks. Parameter ini hanya berarti ketika flag [`AlignText`](./aligntext/) diatur ke true. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)