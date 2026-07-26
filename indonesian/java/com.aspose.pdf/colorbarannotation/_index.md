---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili anotasi ColorBarAnnotation. Properti Color diabaikan, sebagai gantinya digunakan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi."
type: docs
weight: 680
url: /id/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Kelas yang merepresentasikan anotasi ColorBarAnnotation. Properti Color diabaikan, sebagai gantinya digunakan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa apakah persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam kasus ini, anotasi tetap ada di halaman, tetapi tidak ditampilkan).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Membuat anotasi ColorBar baru pada halaman yang ditentukan. Default ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Membuat anotasi ColorBar baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Perbarui parameter dan tampilan, sesuai dengan transformasi matriks dan pemindahan di luar TrimBox jika diperlukan. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getColorOfCMYK](#getColorOfCMYK--) | Mendapatkan atau mengatur warna (salah satu cyan, magenta, yellow, black) yang digunakan untuk menggambar anotasi. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Mendapatkan atau mengatur warna (salah satu cyan, magenta, yellow, black) yang digunakan untuk menggambar anotasi. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Membuat anotasi ColorBar baru pada halaman yang ditentukan. Default ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Membuat anotasi ColorBar baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Perbarui parameter dan tampilan, sesuai dengan transformasi matriks dan pemindahan di luar TrimBox jika diperlukan.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
nilai int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Mendapatkan atau mengatur warna (salah satu cyan, magenta, yellow, black) yang digunakan untuk menggambar anotasi.

**Returns:**
Elemen ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Mendapatkan atau mengatur warna (salah satu cyan, magenta, yellow, black) yang digunakan untuk menggambar anotasi.
