---
title: "Enum XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes enum. Dokumen XSLFO sumber dapat berisi kesalahan format. Enum ini menjenumerasi strategi yang mungkin untuk menangani kesalahan format tersebut"
type: docs
weight: 11730
url: /id/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Dokumen XSLFO sumber dapat berisi kesalahan format. Enum ini menjenumerasi strategi yang mungkin untuk menangani kesalahan format tersebut

```csharp
public enum ParsingErrorsHandlingTypes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| TryIgnore | `0` | Dalam kasus ini konverter akan diinstruksikan untuk mencoba melanjutkan konversi dan mengabaikan kesalahan format yang ditemukan. Dalam kasus ini keberhasilan tidak dijamin, masalah serius dapat terjadi kemudian pada konverter, dan dalam kasus seperti itu akan dilemparkan pengecualian dengan daftar kesalahan format yang ditemukan. |
| ThrowExceptionImmediately | `1` | Dalam kasus ini konversi akan dihentikan segera dan pengecualian akan dilemparkan segera setelah mendeteksi kesalahan format pertama. |
| InvokeCustomHandler | `2` | Ini adalah metode yang paling gesit - kode khusus harus menyediakan (pada properti WarningCallback) penangan khusus yang akan dipanggil ketika kesalahan pemformatan terdeteksi. Penangan tersebut dapat misalnya mencatat atau menghitung kesalahan, dll., dan akan memberikan keputusan apakah pemrosesan dapat dilanjutkan untuk kesalahan ini atau itu. |

### Lihat Juga

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


