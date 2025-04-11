---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy. Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file untuk dokumen ini, perlu untuk mendefinisikan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dari enumerasi ini hanya memiliki arti ketika flag OptimizeFileSize diatur
type: docs
weight: 8400
url: /id/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## Enumerasi PdfFormatConversionOptions.RemoveFontsStrategy

Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file untuk dokumen ini, perlu untuk mendefinisikan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dari enumerasi ini hanya memiliki arti ketika flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) diatur.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Strategi ini menghapus semua font yang memiliki duplikat dalam dokumen. Jika dokumen mengandung kelompok font yang diduplikasi, hanya satu font dari kelompok ini yang disematkan dalam dokumen. Semua font lain dari kelompok ini dihapus dari dokumen, setiap font yang dihapus digantikan dengan analog yang sudah disematkan. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Strategi ini mirip dengan RemoveDuplicatedFonts tetapi tidak menghapus font yang sepenuhnya diduplikasi, melainkan font yang mirip satu sama lain dan hanya berbeda pada parameter "Widths". Parameter ini berisi sekumpulan beberapa lebar untuk simbol tertentu dari font. Setiap nilai lebar dari set "Widths" ini bukanlah lebar nyata dari simbol (glyph), lebar nyata untuk simbol ini sudah ditentukan dalam data biner font. Nilai lebar dari set "Widths" berarti lebar visual untuk simbol ini - lebar yang harus diatur perangkat lunak penampil PDF saat menampilkan simbol, bukan lebar nyata yang ditentukan dalam font. Lebih tepatnya spesifikasi menyatakan: Penampil Acrobat 5.0 dan yang lebih baru menggunakan lebar glyph yang disimpan dalam kamus font untuk menggantikan lebar glyph dalam program font itu sendiri, yang meningkatkan konsistensi tampilan dan pencetakan dokumen. Strategi ini lebih efektif daripada RemoveDuplicatedFonts tetapi penggunaan strategi ini dalam beberapa kasus secara teoritis dapat merusak presentasi visual dokumen yang dikonversi. Defek ini mungkin terjadi karena lebar yang dinyatakan dari font dapat berbeda untuk simbol yang sama dan dalam kasus ini lebar simbol ini akan diubah menjadi yang baru setelah penggantian font - ketika font yang dihapus akan digantikan dalam dokumen dengan yang sudah disematkan. Dan jika lebar visual simbol diubah - itu akan ditampilkan secara tidak benar dan perbedaan ini dapat menyebabkan cacat visual seperti tumpang tindih teks atau masalah lainnya. Namun cacat visual yang dijelaskan adalah kasus yang sangat jarang dan strategi ini mengurangi ukuran dokumen dengan lebih efektif. |
| SubsetFonts | `2` | Ini adalah strategi yang paling efektif untuk mengurangi ukuran dokumen. Ini mengambil set font yang sepenuhnya disematkan dan memangkasnya hanya ke subset yang digunakan. Disarankan untuk menggunakan strategi ini dalam kombinasi dengan RemoveDuplicatedFonts atau RemoveSimilarFontsWithDifferentWidths untuk mendapatkan efek kompresi ganda untuk ukuran file. Penggunaan ketiga strategi secara bersamaan tidak ada artinya dan strategi RemoveSimilarFontsWithDifferentWidths tidak akan digunakan dalam kasus ini. |

### Lihat Juga

* kelas [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)