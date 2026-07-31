---
title: "Kelas PdfFormatConversionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.PdfFormatConversionOptions. mewakili sekumpulan opsi untuk mengonversi dokumen PDF"
type: docs
weight: 8520
url: /id/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

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
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Bendera ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen tidak memengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika bendera ini diaktifkan, operasi perataan khusus akan dilakukan. Bendera ini sebaiknya diaktifkan hanya untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan bendera ini dapat menurunkan kinerja dan dalam beberapa kasus dapat merusak konten teks. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan untuk penandaan otomatis selama konversi format PDF. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Aksi untuk gambar dengan soft mask. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Aksi untuk objek yang tidak dapat dikonversi |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. Parameter ini hanya bermakna ketika bendera [`OptimizeFileSize`](./optimizefilesize/) diatur ke true. Secara default kombinasi strategi SubsetFonts dan RemoveDuplicatedFonts digunakan. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opsi untuk kasus ketika tidak memungkinkan menyematkan beberapa font ke dalam dokumen PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Format PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Mendapatkan atau mengatur nama file profil icc. Jika null, profil icc default akan digunakan. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Mendapatkan/mengatur jalannya aliran gambar dalam mode async. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Apakah mode konversi memori rendah diaktifkan |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Mendapatkan atau mengatur apakah data dari Info harus diteruskan ke Metadata saat dikonversi ke PDF 2.0. True secara default. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Jalur ke file tempat komentar akan disimpan. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Aliran tempat komentar akan disimpan. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Menyimpan bendera untuk mengontrol proses konversi PDF/A untuk kasus ketika dokumen sumber tidak sesuai dengan spesifikasi PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Properti ini adalah properti keluaran. Ini menyimpan semua font (nama font) yang tidak ditemukan di komputer pada konversi PDF/A terakhir. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Mendapatkan atau mengatur bendera yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil. Saat ini bendera ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, dan kemungkinan di masa depan bendera ini juga akan digunakan untuk mengaktifkan optimisasi struktur data lain, seperti grafik. Kombinasi bendera dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan menurunkan kinerja konversi. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Mendapatkan atau mengatur [`OutputIntent`](../outputintent/) untuk konversi format PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategi untuk memproses simbol dari Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable enkoding. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Aksi untuk objek gambar yang dimask. |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Aturan untuk menyelesaikan masalah dengan pemetaan Unicode. Dapat bernilai null. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag [`AlignText`](./aligntext/) diatur ke true. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


