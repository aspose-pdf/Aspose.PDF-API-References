---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Optimization.OptimizationOptions. Kelas yang menggambarkan algoritma optimasi dokumen. Instansi dari kelas ini dapat digunakan sebagai parameter dari metode OptimizeResources
type: docs
weight: 7980
url: /id/net/aspose.pdf.optimization/optimizationoptions/
---
## Kelas OptimizationOptions

Kelas yang menggambarkan algoritma optimasi dokumen. Instansi dari kelas ini dapat digunakan sebagai parameter dari metode OptimizeResources().

```csharp
public class OptimizationOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Jika flag ini diatur ke `true`, objek Pdf akan dikemas ke dalam Objek Stream dan dikompresi untuk mengurangi ukuran file pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Sekumpulan opsi yang menggambarkan apakah gambar dalam dokumen akan dikompresi dan parameter dari kompresi tersebut. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Pengkodean gambar yang akan digunakan. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Jika flag ini diatur ke true, stream sumber daya akan dianalisis. Jika ditemukan stream duplikat (misalnya, jika konten stream sama), maka stream tersebut akan disimpan sebagai satu objek. Ini memungkinkan untuk mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Tingkat pemindaian. Pemindaian yang lebih dalam (nilai lebih tinggi) memakan waktu lebih lama tetapi dapat menghasilkan file hasil yang lebih kecil. Nilai default: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, itu akan diskalakan. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Menghapus informasi pribadi (info bagian halaman). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak digunakan (yaitu, objek yang tidak memiliki referensi) akan dihapus dari dokumen. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Jika flag ini diatur ke true, setiap sumber daya diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut dihapus. Ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Font akan diubah menjadi subset jika diatur ke true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Membuat font tidak tersemat jika diatur ke true. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Membuat strategi optimasi dengan semua opsi diaktifkan. Harap dicatat bahwa hanya opsi yang diaktifkan yang tidak mengubah fungsionalitas dokumen. Misalnya, kompresi gambar dan penghilangan font tidak akan diaktifkan (dan dapat disematkan secara manual). |

### Lihat Juga

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)