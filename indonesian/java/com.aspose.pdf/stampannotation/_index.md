---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili anotasi stempel karet. Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan tampak seolah-olah dicap pada halaman dengan stempel karet. </p> <hr>."
type: docs
weight: 4630
url: /id/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Mewakili anotasi stempel karet. Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan agar terlihat seolah-olah mereka dicap pada halaman dengan stempel karet. </p> <hr> <pre> Potongan kode berikut menunjukkan cara menambahkan 2 stempel ke halaman pertama dokumen pdf. Dokumen input berasal dari inFile dan perubahan disimpan ke outFile. Stempel pertama memiliki ikon NotForPublicRelease dan yang kedua menggunakan gambar dari rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Konstruktor |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Membuat anotasi Stempel baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima {@code AnnotationSelector} visitor saat menelusuri koleksi anotasi. |
| [clear](#clear--) | Bersihkan instance statis |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getIcon](#getIcon--) | Mendapatkan ikon untuk cap karet. |
| [getImage](#getImage--) | Mendapatkan gambar anotasi. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Mengatur gambar SVG anotasi dalam string Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Mengatur ikon untuk cap karet. |
| [setImage](#setImage-java.io.InputStream-) | Mengatur gambar anotasi. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Konstruktor

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Membuat anotasi Stempel baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima {@code AnnotationSelector} visitor saat menelusuri koleksi anotasi.

### clear {#clear--}
```
public static void clear()
```

Bersihkan instance statis

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Mendapatkan ikon untuk cap karet.

**Returns:**
Nilai StampIcon

### getImage {#getImage--}
```
public InputStream getImage()
```

Mendapatkan gambar anotasi.

**Returns:**
Objek InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Mengatur gambar SVG anotasi dalam string Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Mengatur ikon untuk cap karet.

### setImage {#setImage-java.io.InputStream-}
Mengatur gambar anotasi.
