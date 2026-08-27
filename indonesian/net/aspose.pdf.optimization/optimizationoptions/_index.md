---
title: "Kelas OptimizationOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Optimization.OptimizationOptions kelas. Kelas yang menjelaskan algoritma optimasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources."
type: docs
weight: 8120
url: /id/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Kelas yang menjelaskan algoritma optimisasi dokumen. Instance kelas ini dapat digunakan sebagai parameter metode OptimizeResources().

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
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Jika flag ini diatur ke `true`, objek Pdf akan dikemas ke dalam Objest Streams dan dikompresi untuk mengurangi ukuran file pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Sekumpulan opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Enkode gambar yang akan digunakan. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Jika flag ini diatur ke true, Resource streams akan dianalisis. Jika aliran duplikat ditemukan (misalnya jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. Hal ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, maka akan diubah skalanya. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Hapus informasi pribadi (informasi potongan halaman). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (misalnya objek yang tidak memiliki referensi) akan dihapus dari dokumen. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Jika flag ini diatur ke true, setiap resource akan diperiksa penggunaannya. Jika resource tidak pernah digunakan, maka resource tersebut akan dihapus. Hal ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Font akan dikonversi menjadi subset jika diatur ke true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Jadikan font tidak ter-embed jika diatur ke true. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Membuat strategi optimasi dengan semua opsi diaktifkan. Harap perhatikan bahwa hanya opsi yang tidak mengubah fungsi apa pun dari dokumen yang diaktifkan. Misalnya, kompresi gambar dan penghapusan embed font tidak akan diaktifkan (dan dapat di-embed secara manual). |

### Lihat Juga

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


