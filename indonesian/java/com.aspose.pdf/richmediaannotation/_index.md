---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang menggambarkan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF."
type: docs
weight: 4260
url: /id/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Kelas yang menggambarkan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Menginisialisasi RichMediaAnnotation. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima visitor untuk anotasi ini. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Tambahkan data bernama khusus (misalnya diperlukan untuk skrip flash). |
| [getActivateOn](#getActivateOn--) | Acara yang mengaktifkan aplikasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getContent](#getContent--) | Data konten Rich Media. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Mengatur atau mendapatkan variabel flash yang diteruskan ke pemutar. |
| [getCustomPlayer](#getCustomPlayer--) | Mengatur atau mendapatkan pemutar flash khusus untuk memutar data video/audio. |
| [getType](#getType--) | Mendapatkan atau mengatur tipe konten. Nilai yang mungkin: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Acara yang mengaktifkan aplikasi. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Atur aliran konten. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Mengatur atau mendapatkan variabel flash yang diteruskan ke pemutar. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Mengatur atau mendapatkan pemutar flash khusus untuk memutar data video/audio. |
| [setPoster](#setPoster-java.io.InputStream-) | Atur poster anotasi. |
| [setType](#setType-int-) | Mendapatkan atau mengatur tipe konten. Nilai yang mungkin: Audio, Video. |
| [update](#update--) | Memperbarui data dengan parameter yang ditentukan. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Menginisialisasi RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima visitor untuk anotasi ini.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Tambahkan data bernama khusus (misalnya diperlukan untuk skrip flash).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Acara yang mengaktifkan aplikasi.

**Returns:**
ActivationEvent elemen

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Data konten Rich Media.

**Returns:**
Objek InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Mengatur atau mendapatkan variabel flash yang diteruskan ke pemutar.

**Returns:**
Objek String

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Mengatur atau mendapatkan pemutar flash khusus untuk memutar data video/audio.

**Returns:**
Objek InputStream

### getType {#getType--}
```
public int getType()
```

Mendapatkan atau mengatur tipe konten. Nilai yang mungkin: Audio, Video.

**Returns:**
ContentType nilai @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Acara yang mengaktifkan aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | ActivationEvent elemen |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Atur aliran konten.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Mengatur atau mendapatkan variabel flash yang diteruskan ke pemutar.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Mengatur atau mendapatkan pemutar flash khusus untuk memutar data video/audio.

### setPoster {#setPoster-java.io.InputStream-}
Atur poster anotasi.

### setType {#setType-int-}
```
public void setType(int value)
```

Mendapatkan atau mengatur tipe konten. Nilai yang mungkin: Audio, Video.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | ContentType elemen |

### update {#update--}
```
public void update()
```

Memperbarui data dengan parameter yang ditentukan.
