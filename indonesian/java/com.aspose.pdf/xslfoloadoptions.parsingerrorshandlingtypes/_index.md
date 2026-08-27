---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan pemformatan tersebut."
type: docs
weight: 5790
url: /id/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan pemformatan tersebut.

## Fields

| Field | Deskripsi |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Ini adalah metode yang paling gesit - kode khusus harus menyediakan (di properti WarningCallback) penangan khusus yang akan dipanggil ketika kesalahan pemformatan terdeteksi. Penangan tersebut dapat, misalnya, mencatat atau menghitung kesalahan, dll, dan akan memberikan keputusan apakah pemrosesan dapat dilanjutkan untuk kesalahan ini atau itu. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | Dalam kasus ini konversi akan dihentikan segera dan pengecualian akan dilemparkan segera setelah mendeteksi kesalahan pemformatan pertama. |
| [TryIgnore](#TryIgnore) | Dalam kasus ini konverter akan diinstruksikan untuk mencoba melanjutkan konversi dan mengabaikan kesalahan pemformatan yang ditemukan. Dalam kasus ini keberhasilan tidak dijamin, masalah serius dapat terjadi kemudian pada konverter, dan dalam kasus seperti itu pengecualian akan dilemparkan dengan daftar kesalahan pemformatan yang ditemukan. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Ini adalah metode yang paling gesit - kode khusus harus menyediakan (di properti WarningCallback) penangan khusus yang akan dipanggil ketika kesalahan pemformatan terdeteksi. Penangan tersebut dapat, misalnya, mencatat atau menghitung kesalahan, dll, dan akan memberikan keputusan apakah pemrosesan dapat dilanjutkan untuk kesalahan ini atau itu.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

Dalam kasus ini konversi akan dihentikan segera dan pengecualian akan dilemparkan segera setelah mendeteksi kesalahan pemformatan pertama.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

Dalam kasus ini konverter akan diinstruksikan untuk mencoba melanjutkan konversi dan mengabaikan kesalahan pemformatan yang ditemukan. Dalam kasus ini keberhasilan tidak dijamin, masalah serius dapat terjadi kemudian pada konverter, dan dalam kasus seperti itu pengecualian akan dilemparkan dengan daftar kesalahan pemformatan yang ditemukan.
