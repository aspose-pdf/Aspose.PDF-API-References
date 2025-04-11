---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. Dokumen XSLFO sumber dapat mengandung kesalahan format. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan format tersebut.
type: docs
weight: 11540
url: /id/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## Enumerasi XslFoLoadOptions.ParsingErrorsHandlingTypes

Dokumen XSLFO sumber dapat mengandung kesalahan format. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan format tersebut.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| TryIgnore | `0` | Dalam hal ini, konverter akan diarahkan untuk mencoba melanjutkan konversi dan mengabaikan kesalahan format yang ditemukan. Dalam hal ini, keberhasilan tidak dijamin, masalah serius dapat terjadi kemudian di konverter, dan dalam kasus seperti itu akan dilemparkan pengecualian dengan daftar kesalahan format yang ditemukan. |
| ThrowExceptionImmediately | `1` | Dalam hal ini, konversi akan dihentikan segera dan pengecualian akan dilemparkan segera setelah mendeteksi kesalahan format pertama. |
| InvokeCustomHandler | `2` | Ini adalah metode yang paling gesit - kode kustom harus menyediakan (dalam properti WarningCallback) penangan khusus yang akan dipanggil ketika kesalahan format terdeteksi. Penangan tersebut dapat, misalnya, mencatat atau menghitung kesalahan, dll., dan akan memberikan keputusan apakah pemrosesan dapat dilanjutkan untuk kesalahan ini atau itu. |

### Lihat Juga

* kelas [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)