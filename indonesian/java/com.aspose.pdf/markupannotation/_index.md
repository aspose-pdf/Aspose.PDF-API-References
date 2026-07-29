---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas abstrak yang mewakili anotasi markup."
type: docs
weight: 2870
url: /id/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Kelas abstrak yang mewakili anotasi markup.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Konstruktor |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [clearState](#clearState--) | Menghapus state dan state model untuk anotasi. Misalnya, menghapus status tinjauan untuk sebuah anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [getCreationDate](#getCreationDate--) | Mendapatkan tanggal dan waktu saat anotasi dibuat. |
| [getInReplyTo](#getInReplyTo--) | Referensi ke anotasi yang menjadi "balasan" untuk anotasi ini. Kedua anotasi harus berada pada halaman yang sama dalam dokumen. |
| [getOpacity](#getOpacity--) | Mendapatkan nilai opasitas konstan yang akan digunakan saat menggambar anotasi. |
| [getPopup](#getPopup--) | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| [getReplyType](#getReplyType--) | String yang menentukan hubungan ("tipe balasan") antara anotasi ini dan anotasi yang ditentukan oleh InReplyTo. |
| [getRichText](#getRichText--) | Mendapatkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Mendapatkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [getState](#getState--) | Mendapatkan state anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [getStateModel](#getStateModel--) | Mendapatkan state model anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [getSubject](#getSubject--) | Mendapatkan teks yang mewakili deskripsi objek. |
| [getTitle](#getTitle--) | Mendapatkan label teks yang akan ditampilkan di bilah judul jendela pop-up anotasi ketika terbuka dan aktif. Entri ini akan mengidentifikasi pengguna yang menambahkan anotasi. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Mendapatkan tanggal dan waktu saat anotasi dibuat. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Referensi ke anotasi yang menjadi "balasan" untuk anotasi ini. Kedua anotasi harus berada pada halaman yang sama dalam dokumen. |
| [setMarkedState](#setMarkedState-boolean-) | Mengatur state Marked dan Unmarked untuk anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [setOpacity](#setOpacity-double-) | Mengatur nilai opasitas konstan yang akan digunakan saat menggambar anotasi. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | String yang menentukan hubungan ("tipe balasan") antara anotasi ini dan anotasi yang ditentukan oleh InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Mengatur state tinjauan untuk sebuah anotasi. State Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. State ditetapkan oleh pengguna yang membuat anotasi target. Nilainya diambil dari properti Title pada anotasi target. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Mengatur state tinjauan untuk sebuah anotasi. State Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Mengatur string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| [setSubject](#setSubject-java.lang.String-) | Mengatur teks yang mewakili deskripsi objek. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur label teks yang akan ditampilkan di bilah judul jendela pop-up anotasi ketika terbuka dan aktif. Entri ini akan mengidentifikasi pengguna yang menambahkan anotasi. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Konstruktor

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Konstruktor

### clearState {#clearState--}
```
public final void clearState()
```

Menghapus state dan state model untuk anotasi. Misalnya, menghapus status tinjauan untuk sebuah anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Mendapatkan tanggal dan waktu saat anotasi dibuat.

**Returns:**
Objek Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Referensi ke anotasi yang menjadi "balasan" untuk anotasi ini. Kedua anotasi harus berada pada halaman yang sama dalam dokumen.

**Returns:**
Nilai anotasi

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Mendapatkan nilai opasitas konstan yang akan digunakan saat menggambar anotasi.

**Returns:**
nilai double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini.

**Returns:**
Nilai PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

String yang menentukan hubungan ("tipe balasan") antara anotasi ini dan anotasi yang ditentukan oleh InReplyTo.

**Returns:**
ReplyType nilai @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Mendapatkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka.

**Returns:**
nilai String

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Mendapatkan string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka.

**Returns:**
nilai String

### getState {#getState--}
```
public final AnnotationState getState()
```

Mendapatkan state anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

**Returns:**
Status anotasi.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Mendapatkan state model anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

**Returns:**
Model status anotasi.

### getSubject {#getSubject--}
```
public String getSubject()
```

Mendapatkan teks yang mewakili deskripsi objek.

**Returns:**
nilai String

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan label teks yang akan ditampilkan di bilah judul jendela pop-up anotasi ketika terbuka dan aktif. Entri ini akan mengidentifikasi pengguna yang menambahkan anotasi.

**Returns:**
nilai String

### setCreationDate {#setCreationDate-java.util.Date-}
Mendapatkan tanggal dan waktu saat anotasi dibuat.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Referensi ke anotasi yang menjadi "balasan" untuk anotasi ini. Kedua anotasi harus berada pada halaman yang sama dalam dokumen.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Mengatur state Marked dan Unmarked untuk anotasi. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ditandai |  | Benar jika mengatur status Ditandai, dan salah jika mengatur status Tidak Ditandai. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Mengatur nilai opasitas konstan yang akan digunakan saat menggambar anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
String yang menentukan hubungan ("tipe balasan") antara anotasi ini dan anotasi yang ditentukan oleh InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Mengatur state tinjauan untuk sebuah anotasi. State Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. State ditetapkan oleh pengguna yang membuat anotasi target. Nilainya diambil dari properti Title pada anotasi target. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Mengatur state tinjauan untuk sebuah anotasi. State Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. Catatan, state disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

### setRichText {#setRichText-java.lang.String-}
Mengatur string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka.

### setSubject {#setSubject-java.lang.String-}
Mengatur teks yang mewakili deskripsi objek.

### setTitle {#setTitle-java.lang.String-}
Mengatur label teks yang akan ditampilkan di bilah judul jendela pop-up anotasi ketika terbuka dan aktif. Entri ini akan mengidentifikasi pengguna yang menambahkan anotasi.
