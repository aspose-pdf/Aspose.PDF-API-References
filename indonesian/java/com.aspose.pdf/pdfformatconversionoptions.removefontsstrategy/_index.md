---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file dokumen-dokumen ini, perlu mendefinisikan strategi penghapusan font. Enumerasi ini."
type: docs
weight: 3760
url: /id/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file bagi dokumen-dokumen ini, diperlukan penetapan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dalam enumerasi ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur.

## Fields

| Field | Deskripsi |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Strategi ini menghapus semua font yang memiliki duplikat dalam dokumen. Jika dokumen berisi grup font yang duplikat, hanya satu font dari grup tersebut yang disematkan dalam dokumen. Semua font lain dari grup tersebut dihapus dari dokumen, setiap font yang dihapus digantikan dengan analog yang sudah disematkan. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Strategi ini mirip dengan {@code RemoveDuplicatedFonts} tetapi menghapus bukan font yang sepenuhnya duplikat, melainkan font yang mirip satu sama lain dan hanya berbeda pada parameter \"Widths\". Parameter ini berisi sekumpulan lebar tertentu untuk simbol font yang ditentukan. Setiap nilai lebar dari set \"Widths\" ini bukan lebar sebenarnya dari simbol (glyph), lebar sebenarnya untuk simbol tersebut sudah didefinisikan dalam data biner font. Nilai lebar dari set \"Widths\" berarti lebar visual untuk simbol tersebut — lebar yang harus ditetapkan oleh perangkat lunak penampil PDF saat menampilkan simbol menggantikan lebar sebenarnya yang didefinisikan dalam font. Lebih tepatnya spesifikasi menyatakan: penampil Acrobat 5.0 dan yang lebih baru menggunakan lebar glyph yang disimpan dalam kamus font untuk menggantikan lebar glyph dalam program font itu sendiri, yang meningkatkan konsistensi tampilan dan pencetakan dokumen. Strategi ini lebih efektif daripada {@code RemoveDuplicatedFonts} tetapi penggunaan strategi ini dalam beberapa kasus secara teoritis dapat merusak tampilan visual dokumen yang dikonversi. Defek ini mungkin terjadi karena lebar font yang dideklarasikan dapat berbeda untuk simbol yang sama dan dalam kasus ini lebar simbol tersebut akan diubah menjadi baru setelah substitusi font — ketika font yang dihapus akan digantikan dalam dokumen dengan yang sudah disematkan. Dan jika lebar visual simbol berubah — akan ditampilkan secara tidak tepat dan perbedaan ini dapat menyebabkan cacat visual seperti tumpang tindih teks atau masalah lainnya. Namun cacat visual yang dijelaskan sangat jarang terjadi dan strategi ini mengurangi ukuran dokumen secara lebih efektif. |
| [SubsetFonts](#SubsetFonts) | Ini adalah strategi paling efektif untuk mengurangi ukuran dokumen. Strategi ini mengambil set font yang sepenuhnya disematkan dan memangkasnya menjadi hanya subset yang digunakan. Disarankan menggunakan strategi ini bersama dengan {@code RemoveDuplicatedFonts} atau {@code RemoveSimilarFontsWithDifferentWidths} untuk mendapatkan efek kompresi ganda pada ukuran file. Menggunakan ketiga strategi secara bersamaan tidak masuk akal dan strategi {@code RemoveSimilarFontsWithDifferentWidths} tidak akan digunakan dalam kasus ini. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Strategi ini menghapus semua font yang memiliki duplikat dalam dokumen. Jika dokumen berisi grup font yang duplikat, hanya satu font dari grup tersebut yang disematkan dalam dokumen. Semua font lain dari grup tersebut dihapus dari dokumen, setiap font yang dihapus digantikan dengan analog yang sudah disematkan.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Strategi ini mirip dengan {@code RemoveDuplicatedFonts} tetapi menghapus bukan font yang sepenuhnya duplikat, melainkan font yang mirip satu sama lain dan hanya berbeda pada parameter \"Widths\". Parameter ini berisi sekumpulan lebar tertentu untuk simbol font yang ditentukan. Setiap nilai lebar dari set \"Widths\" ini bukan lebar sebenarnya dari simbol (glyph), lebar sebenarnya untuk simbol tersebut sudah didefinisikan dalam data biner font. Nilai lebar dari set \"Widths\" berarti lebar visual untuk simbol tersebut — lebar yang harus ditetapkan oleh perangkat lunak penampil PDF saat menampilkan simbol menggantikan lebar sebenarnya yang didefinisikan dalam font. Lebih tepatnya spesifikasi menyatakan: penampil Acrobat 5.0 dan yang lebih baru menggunakan lebar glyph yang disimpan dalam kamus font untuk menggantikan lebar glyph dalam program font itu sendiri, yang meningkatkan konsistensi tampilan dan pencetakan dokumen. Strategi ini lebih efektif daripada {@code RemoveDuplicatedFonts} tetapi penggunaan strategi ini dalam beberapa kasus secara teoritis dapat merusak tampilan visual dokumen yang dikonversi. Defek ini mungkin terjadi karena lebar font yang dideklarasikan dapat berbeda untuk simbol yang sama dan dalam kasus ini lebar simbol tersebut akan diubah menjadi baru setelah substitusi font — ketika font yang dihapus akan digantikan dalam dokumen dengan yang sudah disematkan. Dan jika lebar visual simbol berubah — akan ditampilkan secara tidak tepat dan perbedaan ini dapat menyebabkan cacat visual seperti tumpang tindih teks atau masalah lainnya. Namun cacat visual yang dijelaskan sangat jarang terjadi dan strategi ini mengurangi ukuran dokumen secara lebih efektif.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Ini adalah strategi paling efektif untuk mengurangi ukuran dokumen. Strategi ini mengambil set font yang sepenuhnya disematkan dan memangkasnya menjadi hanya subset yang digunakan. Disarankan menggunakan strategi ini bersama dengan {@code RemoveDuplicatedFonts} atau {@code RemoveSimilarFontsWithDifferentWidths} untuk mendapatkan efek kompresi ganda pada ukuran file. Menggunakan ketiga strategi secara bersamaan tidak masuk akal dan strategi {@code RemoveSimilarFontsWithDifferentWidths} tidak akan digunakan dalam kasus ini.
