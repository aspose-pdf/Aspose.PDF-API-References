---
title: "Enum PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file dokumen-dokumen ini diperlukan mendefinisikan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi-strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dalam enumerasi ini hanya bermakna ketika flag OptimizeFileSize diatur."
type: docs
weight: 8540
url: /id/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file dokumen-dokumen ini diperlukan mendefinisikan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dalam enumerasi ini hanya bermakna ketika flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) diatur.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Strategi ini menghapus semua font yang memiliki duplikat dalam dokumen. Jika dokumen berisi grup font yang diduplikasi, hanya satu font dari grup tersebut yang disematkan dalam dokumen. Semua font lain dari grup tersebut dihapus dari dokumen, setiap font yang dihapus digantikan dengan analog yang sudah disematkan. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Strategi ini mirip dengan RemoveDuplicatedFonts tetapi menghapus bukan font yang sepenuhnya duplikat melainkan font yang serupa satu sama lain dan hanya berbeda pada parameter "Widths". Parameter ini berisi sekumpulan lebar untuk simbol tertentu pada font. Setiap nilai lebar dari set "Widths" ini bukan lebar sebenarnya dari simbol (glyph), melainkan lebar visual untuk simbol tersebut - lebar yang harus ditetapkan oleh perangkat lunak penampil PDF saat menampilkan simbol alih-alih lebar sebenarnya yang didefinisikan dalam font. Lebih tepatnya spesifikasi menyatakan: penampil Acrobat 5.0 dan yang lebih baru menggunakan lebar glyph yang disimpan dalam kamus font untuk mengganti lebar glyph dalam program font itu sendiri, yang meningkatkan konsistensi tampilan dan pencetakan dokumen. Strategi ini lebih efektif daripada RemoveDuplicatedFonts tetapi penggunaan strategi ini dalam beberapa kasus secara teoritis dapat merusak presentasi visual dokumen yang dikonversi. Defek ini mungkin terjadi karena lebar font yang dideklarasikan dapat berbeda untuk simbol yang sama dan dalam kasus ini lebar simbol tersebut akan diubah menjadi baru setelah substitusi font - ketika font yang dihapus digantikan dalam dokumen dengan yang sudah disematkan. Dan jika lebar visual simbol berubah - ia akan ditampilkan secara tidak benar dan perbedaan ini dapat menyebabkan cacat visual seperti tumpang tindih teks atau masalah lainnya. Namun cacat visual yang dijelaskan sangat jarang terjadi dan strategi ini mengurangi ukuran dokumen secara lebih efektif. |
| SubsetFonts | `2` | Ini adalah strategi paling efektif untuk mengurangi ukuran dokumen. Strategi ini mengambil set font yang sepenuhnya disematkan dan memangkasnya menjadi hanya subset yang digunakan. Disarankan menggunakan strategi ini bersama dengan RemoveDuplicatedFonts atau RemoveSimilarFontsWithDifferentWidths untuk mendapatkan efek kompresi ganda pada ukuran file. Menggunakan ketiga strategi secara bersamaan tidak ada gunanya dan strategi RemoveSimilarFontsWithDifferentWidths tidak akan digunakan dalam kasus ini. |

### Lihat Juga

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


