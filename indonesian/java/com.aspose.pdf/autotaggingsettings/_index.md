---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menyediakan pengaturan untuk fungsi auto-tagging dalam dokumen PDF. Kelas {@link AutoTaggingSettings} memungkinkan mengonfigurasi opsi untuk penandaan otomatis konten PDF. Itu."
type: docs
weight: 230
url: /id/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Menyediakan pengaturan untuk fungsi auto-tagging dalam dokumen PDF. Kelas {@link AutoTaggingSettings} memungkinkan konfigurasi opsi untuk penandaan otomatis konten PDF. Ini mencakup properti untuk mengaktifkan atau menonaktifkan auto-tagging, menentukan strategi untuk pengenalan heading, dan mendefinisikan tingkat heading berdasarkan ukuran font.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDefault](#getDefault--) | Mendapatkan pengaturan default untuk fungsi auto-tagging dalam dokumen PDF. Pengaturan default mengaktifkan auto-tagging dan menggunakan strategi otomatis untuk pengenalan heading. Pengaturan ini dapat digunakan sebagai konfigurasi dasar untuk konversi format PDF atau operasi lain yang memerlukan penandaan otomatis konten PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah fungsi auto-tagging diaktifkan. Ketika diaktifkan, fungsi auto-tagging secara otomatis menghasilkan konten yang ditandai untuk dokumen PDF, yang dapat meningkatkan aksesibilitas dan struktur. |
| [getHeadingLevels](#getHeadingLevels--) | Mendapatkan atau mengatur level heading yang digunakan untuk menentukan struktur heading dalam dokumen PDF. Properti {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) memungkinkan mengonfigurasi pemetaan ukuran font ke level heading. Ini digunakan selama proses auto-tagging untuk mengidentifikasi dan menetapkan level heading yang tepat berdasarkan ukuran font elemen teks dalam dokumen. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Mendapatkan atau mengatur strategi yang digunakan untuk mengenali heading dalam dokumen selama auto-tagging. Properti {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) menentukan bagaimana heading diidentifikasi dalam dokumen. Strategi yang tersedia meliputi mengenali heading berdasarkan outline, analisis heuristik, atau deteksi otomatis. Mengatur properti ini ke {@link HeadingRecognitionStrategy#None} menonaktifkan pengenalan heading. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah fungsi auto-tagging diaktifkan. Ketika diaktifkan, fungsi auto-tagging secara otomatis menghasilkan konten yang ditandai untuk dokumen PDF, yang dapat meningkatkan aksesibilitas dan struktur. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Mendapatkan atau mengatur level heading yang digunakan untuk menentukan struktur heading dalam dokumen PDF. Properti {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) memungkinkan mengonfigurasi pemetaan ukuran font ke level heading. Ini digunakan selama proses auto-tagging untuk mengidentifikasi dan menetapkan level heading yang tepat berdasarkan ukuran font elemen teks dalam dokumen. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Mendapatkan atau mengatur strategi yang digunakan untuk mengenali heading dalam dokumen selama auto-tagging. Properti {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) menentukan bagaimana heading diidentifikasi dalam dokumen. Strategi yang tersedia meliputi mengenali heading berdasarkan outline, analisis heuristik, atau deteksi otomatis. Mengatur properti ini ke {@link HeadingRecognitionStrategy#None} menonaktifkan pengenalan heading. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Mendapatkan pengaturan default untuk fungsi auto-tagging dalam dokumen PDF. Pengaturan default mengaktifkan auto-tagging dan menggunakan strategi otomatis untuk pengenalan heading. Pengaturan ini dapat digunakan sebagai konfigurasi dasar untuk konversi format PDF atau operasi lain yang memerlukan penandaan otomatis konten PDF.

**Returns:**
Instansi AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah fungsi auto-tagging diaktifkan. Ketika diaktifkan, fungsi auto-tagging secara otomatis menghasilkan konten yang ditandai untuk dokumen PDF, yang dapat meningkatkan aksesibilitas dan struktur.

**Returns:**
nilai boolean

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Mendapatkan atau mengatur level heading yang digunakan untuk menentukan struktur heading dalam dokumen PDF. Properti {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) memungkinkan mengonfigurasi pemetaan ukuran font ke level heading. Ini digunakan selama proses auto-tagging untuk mengidentifikasi dan menetapkan level heading yang tepat berdasarkan ukuran font elemen teks dalam dokumen.

**Returns:**
Instansi HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Mendapatkan atau mengatur strategi yang digunakan untuk mengenali heading dalam dokumen selama auto-tagging. Properti {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) menentukan bagaimana heading diidentifikasi dalam dokumen. Strategi yang tersedia meliputi mengenali heading berdasarkan outline, analisis heuristik, atau deteksi otomatis. Mengatur properti ini ke {@link HeadingRecognitionStrategy#None} menonaktifkan pengenalan heading.

**Returns:**
Elemen HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah fungsi auto-tagging diaktifkan. Ketika diaktifkan, fungsi auto-tagging secara otomatis menghasilkan konten yang ditandai untuk dokumen PDF, yang dapat meningkatkan aksesibilitas dan struktur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Mendapatkan atau mengatur level heading yang digunakan untuk menentukan struktur heading dalam dokumen PDF. Properti {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) memungkinkan mengonfigurasi pemetaan ukuran font ke level heading. Ini digunakan selama proses auto-tagging untuk mengidentifikasi dan menetapkan level heading yang tepat berdasarkan ukuran font elemen teks dalam dokumen.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Mendapatkan atau mengatur strategi yang digunakan untuk mengenali heading dalam dokumen selama auto-tagging. Properti {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) menentukan bagaimana heading diidentifikasi dalam dokumen. Strategi yang tersedia meliputi mengenali heading berdasarkan outline, analisis heuristik, atau deteksi otomatis. Mengatur properti ini ke {@link HeadingRecognitionStrategy#None} menonaktifkan pengenalan heading.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen HeadingRecognitionStrategy |
