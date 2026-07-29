---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini mewakili opsi penyimpanan untuk penyimpanan yang menggunakan cara konversi terpadu (dengan model dokumen internal terpadu)."
type: docs
weight: 5420
url: /id/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Kelas ini mewakili opsi penyimpanan untuk penyimpanan yang menggunakan cara konversi terpadu (dengan model dokumen internal terpadu).

## Fields

| Field | Deskripsi |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Proses halaman dengan beberapa thread. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Mewakili pemroses peristiwa kemajuan internal yang bekerja selama konversi dan menerjemahkan peristiwa konversi dari tahap konversi internal menjadi peristiwa kemajuan total eksternal. Kelas ini juga menyiarkan peristiwa yang memungkinkan pembebasan sumber daya yang tidak lagi diperlukan. Kelas internal ini menangani peristiwa kemajuan dari PDF ke APS dan APS ke [Other format] untuk menghitung kemajuan total dan memberi tahu kode pelanggan tentang peristiwa kemajuan total tersebut. Kelas ini menggunakan dua jenis peristiwa: konversi model ApsToExternal dan peristiwa konversi PDF ke APS untuk menghasilkan peristiwa kemajuan total. Ekspor memiliki tiga tahap: 1) PDF ke APS 2) pengenalan APS 3) ekspor APS ke format target. Konstruktor memungkinkan penyesuaian berapa banyak halaman yang dikonversi dan perkiraan bagian dari tahap ini atau itu dalam kemajuan total. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Atribut ini mengaktifkan fungsi untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublapisan OCR. Nilai: {@code true} teks akan diekstrak dalam dokumen hasil; jika tidak, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Terkadang PDF berisi gambar latar (halaman atau sel tabel) yang dibangun dari beberapa gambar latar berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampaknya dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan tersebut. PERHATIAN! Optimasi kualitas ini biasanya memperlambat konversi secara signifikan, jadi, harap gunakan opsi ini hanya bila benar‑benar diperlukan. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks pada dokumen PDF dengan sublapisan OCR. </p>Nilai: {@code true} teks akan diekstrak dalam dokumen hasil; jika tidak, {@code false}. <hr> Nilai default == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Mewakili pemroses peristiwa kemajuan internal yang bekerja selama konversi dan menerjemahkan peristiwa konversi dari tahap konversi internal menjadi peristiwa kemajuan total eksternal. Kelas ini juga menyiarkan peristiwa yang memungkinkan pembebasan sumber daya yang tidak lagi diperlukan. Kelas internal ini menangani peristiwa kemajuan dari PDF ke APS dan APS ke [Other format] untuk menghitung kemajuan total dan memberi tahu kode pelanggan tentang peristiwa kemajuan total tersebut. Kelas ini menggunakan dua jenis peristiwa: konversi model ApsToExternal dan peristiwa konversi PDF ke APS untuk menghasilkan peristiwa kemajuan total. Ekspor memiliki tiga tahap: 1) PDF ke APS 2) pengenalan APS 3) ekspor APS ke format target. Konstruktor memungkinkan penyesuaian berapa banyak halaman yang dikonversi dan perkiraan bagian dari tahap ini atau itu dalam kemajuan total. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Terkadang PDF berisi gambar latar (halaman atau sel tabel) yang dibangun dari beberapa gambar latar berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampaknya dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan tersebut. PERHATIAN! Optimasi kualitas ini biasanya memperlambat konversi secara signifikan, jadi, harap gunakan opsi ini hanya bila benar‑benar diperlukan. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Proses halaman dengan beberapa thread.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Mewakili pemroses peristiwa kemajuan internal yang bekerja selama konversi dan menerjemahkan peristiwa konversi dari tahap konversi internal menjadi peristiwa kemajuan total eksternal. Kelas ini juga menyiarkan peristiwa yang memungkinkan pembebasan sumber daya yang tidak lagi diperlukan. Kelas internal ini menangani peristiwa kemajuan dari PDF ke APS dan APS ke [Other format] untuk menghitung kemajuan total dan memberi tahu kode pelanggan tentang peristiwa kemajuan total tersebut. Kelas ini menggunakan dua jenis peristiwa: konversi model ApsToExternal dan peristiwa konversi PDF ke APS untuk menghasilkan peristiwa kemajuan total. Ekspor memiliki tiga tahap: 1) PDF ke APS 2) pengenalan APS 3) ekspor APS ke format target. Konstruktor memungkinkan penyesuaian berapa banyak halaman yang dikonversi dan perkiraan bagian dari tahap ini atau itu dalam kemajuan total.

**Returns:**
ConversionProgressEventsTranslator instansi

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Atribut ini mengaktifkan fungsi untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublapisan OCR. Nilai: {@code true} teks akan diekstrak dalam dokumen hasil; jika tidak, {@code false}.

**Returns:**
nilai boolean

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Terkadang PDF berisi gambar latar (halaman atau sel tabel) yang dibangun dari beberapa gambar latar berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampaknya dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan tersebut. PERHATIAN! Optimasi kualitas ini biasanya memperlambat konversi secara signifikan, jadi, harap gunakan opsi ini hanya bila benar‑benar diperlukan.

**Returns:**
nilai boolean

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks pada dokumen PDF dengan sublapisan OCR. </p>Nilai: {@code true} teks akan diekstrak dalam dokumen hasil; jika tidak, {@code false}. <hr> Nilai default == false

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Mewakili pemroses peristiwa kemajuan internal yang bekerja selama konversi dan menerjemahkan peristiwa konversi dari tahap konversi internal menjadi peristiwa kemajuan total eksternal. Kelas ini juga menyiarkan peristiwa yang memungkinkan pembebasan sumber daya yang tidak lagi diperlukan. Kelas internal ini menangani peristiwa kemajuan dari PDF ke APS dan APS ke [Other format] untuk menghitung kemajuan total dan memberi tahu kode pelanggan tentang peristiwa kemajuan total tersebut. Kelas ini menggunakan dua jenis peristiwa: konversi model ApsToExternal dan peristiwa konversi PDF ke APS untuk menghasilkan peristiwa kemajuan total. Ekspor memiliki tiga tahap: 1) PDF ke APS 2) pengenalan APS 3) ekspor APS ke format target. Konstruktor memungkinkan penyesuaian berapa banyak halaman yang dikonversi dan perkiraan bagian dari tahap ini atau itu dalam kemajuan total.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Terkadang PDF berisi gambar latar (halaman atau sel tabel) yang dibangun dari beberapa gambar latar berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, perender format target (misalnya MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampaknya dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan tersebut. PERHATIAN! Optimasi kualitas ini biasanya memperlambat konversi secara signifikan, jadi, harap gunakan opsi ini hanya bila benar‑benar diperlukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | nilai boolean |
