---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.LoadOptionsResourceLoadingResult. Hasil dari pemuatan sumber kustom
type: docs
weight: 6150
url: /id/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## Kelas LoadOptions.ResourceLoadingResult

Hasil dari pemuatan sumber kustom

```csharp
public class ResourceLoadingResult
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Membuat instance dari hasil pemuatan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Data biner yang dimuat dengan pemuat kustom - harus diatur setelah pemuatan |

## Field

| Nama | Deskripsi |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Terkadang encoding sumber diketahui setelah atau selama pemuatan. Dalam kasus seperti itu, kode kustom dapat memberikan konverter dengan pengetahuan itu melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Terkadang tidak mungkin untuk memuat sumber yang diminta karena suatu alasan. Ketidaktersediaan sumber sering kali tidak menyebabkan kerusakan pada konversi dan dokumen hasil dapat dibuat meskipun (tetapi mungkin dalam kualitas yang sedikit lebih buruk, tanpa gambar, dll.). Jika pengecualian terjadi selama pemuatan, cukup tangkap dan masukkan ke dalam parameter ini - terkadang informasi itu berguna bagi konverter untuk merender hasil. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Terkadang karena beberapa alasan pemuatan tidak boleh terjadi pada kode kustom. Dalam kasus seperti itu, silakan atur bendera ini sebagai True. Dalam kasus seperti itu, konverter akan mencoba menggunakan pemuat sumber default internal untuk mendapatkan hasil itu (seperti yang dilakukannya dalam situasi ketika strategi kustom tidak disuplai). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Terkadang pengetahuan tentang tipe MIME dari sumber yang dimuat berguna bagi konverter. Anda dapat memberikan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Silakan biarkan parameter sama dengan null ketika tipe MIME tidak diketahui atau tidak perlu disuplai. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)