---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, ..."
type: docs
weight: 3090
url: /id/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Mewakili anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor untuk digunakan dengan Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Membuat anotasi Sound baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getAspect](#getAspect--) | Mendapatkan atau mengatur lebar dan tinggi kotak pembatas film, dalam piksel. |
| [getFile](#getFile--) | Mendapatkan spesifikasi file yang mengidentifikasi file film yang mendeskripsikan dirinya sendiri. |
| [getPoster](#getPoster--) | Mendapatkan atau mengatur flag atau aliran yang menentukan apakah dan bagaimana gambar poster yang mewakili film akan ditampilkan. Jika true, gambar poster akan diambil dari file film; jika false, tidak ada poster yang akan ditampilkan. |
| [getRotate](#getRotate--) | Mendapatkan atau mengatur jumlah derajat di mana film akan diputar searah jarum jam relatif terhadap halaman. Nilainya harus kelipatan 90. |
| [getTitle](#getTitle--) | Mendapatkan judul anotasi film. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Mendapatkan atau mengatur lebar dan tinggi kotak pembatas film, dalam piksel. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Mengatur spesifikasi file yang mengidentifikasi file film yang mendeskripsikan dirinya sendiri. |
| [setPoster](#setPoster-boolean-) | Mendapatkan atau mengatur flag atau aliran yang menentukan apakah dan bagaimana gambar poster yang mewakili film akan ditampilkan. Jika true, gambar poster akan diambil dari file film; jika false, tidak ada poster yang akan ditampilkan. |
| [setRotate](#setRotate-int-) | Mendapatkan atau mengatur jumlah derajat di mana film akan diputar searah jarum jam relatif terhadap halaman. Nilainya harus kelipatan 90. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur judul anotasi film. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor untuk digunakan dengan Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Membuat anotasi Sound baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType sebagai nilai int @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Mendapatkan atau mengatur lebar dan tinggi kotak pembatas film, dalam piksel.

**Returns:**
Instansi Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Mendapatkan spesifikasi file yang mengidentifikasi file film yang mendeskripsikan dirinya sendiri.

**Returns:**
Nilai FileSpecification

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Mendapatkan atau mengatur flag atau aliran yang menentukan apakah dan bagaimana gambar poster yang mewakili film akan ditampilkan. Jika true, gambar poster akan diambil dari file film; jika false, tidak ada poster yang akan ditampilkan.

**Returns:**
nilai boolean

### getRotate {#getRotate--}
```
public final int getRotate()
```

Mendapatkan atau mengatur jumlah derajat di mana film akan diputar searah jarum jam relatif terhadap halaman. Nilainya harus kelipatan 90.

**Returns:**
nilai int

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan judul anotasi film.

**Returns:**
nilai String

### setAspect {#setAspect-com.aspose.pdf.Point-}
Mendapatkan atau mengatur lebar dan tinggi kotak pembatas film, dalam piksel.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Mengatur spesifikasi file yang mengidentifikasi file film yang mendeskripsikan dirinya sendiri.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Mendapatkan atau mengatur flag atau aliran yang menentukan apakah dan bagaimana gambar poster yang mewakili film akan ditampilkan. Jika true, gambar poster akan diambil dari file film; jika false, tidak ada poster yang akan ditampilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Mendapatkan atau mengatur jumlah derajat di mana film akan diputar searah jarum jam relatif terhadap halaman. Nilainya harus kelipatan 90.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTitle {#setTitle-java.lang.String-}
Mengatur judul anotasi film.
