---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili anotasi suara yang berisi suara yang direkam dari mikrofon komputer atau diimpor dari file."
type: docs
weight: 4530
url: /id/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Mewakili anotasi suara yang berisi suara yang direkam dari mikrofon komputer atau diimpor dari file.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Membuat anotasi Sound baru pada halaman yang ditentukan. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Membuat anotasi Sound baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getIcon](#getIcon--) | Mendapatkan ikon yang akan digunakan untuk menampilkan anotasi. |
| [getSoundData](#getSoundData--) | Mendapatkan objek suara yang menentukan suara yang akan diputar ketika anotasi diaktifkan. |
| [setIcon](#setIcon-int-) | Mengatur ikon yang akan digunakan untuk menampilkan anotasi. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Membuat anotasi Sound baru pada halaman yang ditentukan.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Membuat anotasi Sound baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Nilai AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Mendapatkan ikon yang akan digunakan untuk menampilkan anotasi.

**Returns:**
Nilai SoundIcon @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Mendapatkan objek suara yang menentukan suara yang akan diputar ketika anotasi diaktifkan.

**Returns:**
Nilai SoundData

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Mengatur ikon yang akan digunakan untuk menampilkan anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai SoundIcon @see SoundIcon |
