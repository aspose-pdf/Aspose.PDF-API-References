---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 4720
url: /id/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Opsi penyimpanan untuk ekspor ke format SVG

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, harap atur flag 'CustomProcessingCancelled' pada variabel parameter 'imageSavingInfo' dalam kode khusus. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg halaman untuk dokumen sumber multi-halaman, yang juga diterapkan pada set file output yang di-zip. |
| [isScaleToPixels](#isScaleToPixels--) | Menentukan apakah akan mengubah skala dokumen output dari poin tipografi ke piksel. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Opsi ini menentukan apakah akan dibuat direktori target (jika belum ada) dengan nama yang sama dengan file output yang diminta alih-alih file output itu sendiri. Dengan begitu, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah). Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output "C:\\AsposeTests\\output.svg" dan output akan berisi beberapa file svg halaman, maka file halaman juga akan dibuat di direktori "C:\\AsposeTests\\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg halaman untuk dokumen sumber multi-halaman, yang juga diterapkan pada set file output yang di-zip. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Menentukan apakah akan mengubah skala dokumen output dari poin tipografi ke piksel. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Opsi ini menentukan apakah akan dibuat direktori target (jika belum ada) dengan nama yang sama dengan file output yang diminta alih-alih file output itu sendiri. Dengan begitu, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah). Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output "C:\\AsposeTests\\output.svg" dan output akan berisi beberapa file svg halaman, maka file halaman juga akan dibuat di direktori "C:\\AsposeTests\\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Konstruktor

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, harap atur flag 'CustomProcessingCancelled' pada variabel parameter 'imageSavingInfo' dalam kode khusus. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun.

**Returns:**
EmbeddedImagesSavingStrategy instance

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg halaman untuk dokumen sumber multi-halaman, yang juga diterapkan pada set file output yang di-zip.

**Returns:**
nilai boolean

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Menentukan apakah akan mengubah skala dokumen output dari poin tipografi ke piksel.

**Returns:**
nilai boolean

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Opsi ini menentukan apakah akan dibuat direktori target (jika belum ada) dengan nama yang sama dengan file output yang diminta alih-alih file output itu sendiri. Dengan begitu, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah). Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output "C:\AsposeTests\output.svg" dan output akan berisi beberapa file svg halaman, maka file halaman juga akan dibuat di direktori "C:\AsposeTests\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll.

**Returns:**
nilai boolean

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Menentukan apakah output akan dibuat sebagai satu arsip zip. Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan file svg halaman untuk dokumen sumber multi-halaman, yang juga diterapkan pada set file output yang di-zip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressOutputToZipArchive |  | nilai boolean |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Menentukan apakah akan mengubah skala dokumen output dari poin tipografi ke piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleToPixels |  | nilai boolean |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Opsi ini menentukan apakah akan dibuat direktori target (jika belum ada) dengan nama yang sama dengan file output yang diminta alih-alih file output itu sendiri. Dengan begitu, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah). Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output "C:\AsposeTests\output.svg" dan output akan berisi beberapa file svg halaman, maka file halaman juga akan dibuat di direktori "C:\AsposeTests\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | nilai boolean |
