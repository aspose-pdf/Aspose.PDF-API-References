---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Plugins.PdfAOptionsBase. Mewakili kelas dasar untuk opsi plugin PdfAConverter. Kelas ini menyediakan properti dan metode untuk mengonfigurasi proses konversi dan validasi PDF/A
type: docs
weight: 9010
url: /id/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## Kelas PdfAOptionsBase

Mewakili kelas dasar untuk opsi plugin [`PdfAConverter`](../pdfaconverter/). Kelas ini menyediakan properti dan metode untuk mengonfigurasi proses konversi dan validasi PDF/A.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Mengambil atau menetapkan nilai yang menunjukkan apakah cara tambahan diperlukan untuk mempertahankan penyelarasan teks selama proses konversi PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Mengambil atau menetapkan tindakan yang akan diambil untuk objek yang tidak dapat dikonversi. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Mengambil atau menetapkan strategi untuk menghapus font untuk meminimalkan ukuran file keluaran selama proses konversi PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Mengambil opsi untuk memproses font yang tidak dapat disematkan ke dalam dokumen. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Mengambil atau menetapkan nama file profil ICC (International Color Consortium) yang akan digunakan untuk konversi PDF/A sebagai pengganti yang default. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Mengambil koleksi sumber data |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Mengambil atau menetapkan nilai yang menunjukkan apakah mode memori rendah diaktifkan selama proses konversi PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Mengambil atau menetapkan sumber data untuk keluaran log. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Mengambil bendera yang mengontrol konversi PDF/A untuk kasus ketika dokumen PDF sumber tidak sesuai dengan spesifikasi PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Mengambil atau menetapkan nilai yang menunjukkan apakah akan mencoba mengurangi ukuran file selama proses konversi PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Mengambil atau menetapkan versi standar PDF/A yang akan digunakan untuk validasi atau konversi. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Mengambil atau menetapkan strategi untuk memproses simbol Area Penggunaan Pribadi (PUA) dalam dokumen PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Mengambil atau menetapkan tindakan yang akan diambil selama konversi gambar dengan masker lembut. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Mengambil atau menetapkan strategi untuk pengkodean font simbolik saat mengonversi ke format PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Mengambil atau menetapkan aturan untuk memproses tabel CMap ToUnicode dan tidak terhubung ke simbol Unicode selama proses konversi PDF/A. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi |

### Lihat Juga

* antarmuka [IPluginOptions](../ipluginoptions/)
* ruang nama [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)