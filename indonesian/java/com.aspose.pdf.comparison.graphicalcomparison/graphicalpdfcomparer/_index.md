---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk membandingkan dokumen PDF secara grafis. Harus digunakan untuk mencari perubahan kecil, terutama yang bersifat grafis. Untuk membandingkan perubahan konten teks, gunakan yang lain."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Mewakili kelas untuk membandingkan dokumen PDF secara grafis. Harus digunakan untuk mencari perubahan kecil, terutama yang bersifat grafis. Untuk membandingkan perubahan konten teks, gunakan kelas perbandingan PDF lainnya.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Membuat instance dari kelas {@link GraphicalPdfComparer}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Membandingkan dokumen secara grafis. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam sebuah gambar. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF. |
| [getColor](#getColor--) | Mendapatkan dan mengatur warna bendera perubahan. Warna default adalah merah. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Mendapatkan perbedaan antara gambar halaman. Hasilnya berisi gambar halaman pertama yang dibandingkan dan array perbedaan. |
| [getResolution](#getResolution--) | Mendapatkan dan mengatur resolusi gambar hasil. Nilai default adalah 150dpi. |
| [getThreshold](#getThreshold--) | Mendapatkan dan mengatur nilai ambang dalam persentase. Nilai ini memungkinkan Anda mengabaikan perubahan kecil jika tidak signifikan bagi Anda. Nilai default adalah 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Mendapatkan dan mengatur warna bendera perubahan. Warna default adalah merah. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Mendapatkan dan mengatur resolusi gambar hasil. Nilai default adalah 150dpi. |
| [setThreshold](#setThreshold-double-) | Mendapatkan dan mengatur nilai ambang dalam persentase. Nilai ini memungkinkan Anda mengabaikan perubahan kecil jika tidak signifikan bagi Anda. Nilai default adalah 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Membuat instance dari kelas {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Membandingkan dokumen secara grafis.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Membandingkan dokumen secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam sebuah gambar.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Membandingkan halaman secara grafis. Hasil perbandingan ditempatkan dalam dokumen PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

Mendapatkan dan mengatur warna bendera perubahan. Warna default adalah merah.

**Returns:**
Instansi Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Mendapatkan perbedaan antara gambar halaman. Hasilnya berisi gambar halaman pertama yang dibandingkan dan array perbedaan.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Mendapatkan dan mengatur resolusi gambar hasil. Nilai default adalah 150dpi.

**Returns:**
Instansi Resolusi

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Mendapatkan dan mengatur nilai ambang dalam persentase. Nilai ini memungkinkan Anda mengabaikan perubahan kecil jika tidak signifikan bagi Anda. Nilai default adalah 0%.

**Returns:**
nilai double

### setColor {#setColor-com.aspose.pdf.Color-}
Mendapatkan dan mengatur warna bendera perubahan. Warna default adalah merah.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Mendapatkan dan mengatur resolusi gambar hasil. Nilai default adalah 150dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Mendapatkan dan mengatur nilai ambang dalam persentase. Nilai ini memungkinkan Anda mengabaikan perubahan kecil jika tidak signifikan bagi Anda. Nilai default adalah 0%.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |
