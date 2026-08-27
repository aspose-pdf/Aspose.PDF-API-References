---
title: "Kelas LoadOptions.ResourceLoadingResult"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.LoadOptionsResourceLoadingResult. Hasil pemuatan khusus sumber daya"
type: docs
weight: 6290
url: /id/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Hasil pemuatan khusus sumber daya

```csharp
public class ResourceLoadingResult
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Membuat instance hasil pemuatan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Data biner yang dimuat dengan pemuat khusus - harus diatur setelah pemuatan |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Kadang encoding sumber daya diketahui setelah atau selama pemuatan. Dalam kasus tersebut kode khusus dapat memberikan konverter pengetahuan tersebut melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Kadang tidak mungkin memuat sumber daya yang diminta karena suatu alasan. Ketidtersediaan sumber daya sering tidak menyebabkan kegagalan konversi dan dokumen hasil tetap dapat dibuat (meskipun mungkin dengan kualitas sedikit lebih buruk, tanpa gambar, dll.). Jika pengecualian terjadi selama pemuatan, cukup tangkap dan masukkan ke dalam parameter ini - kadang informasi tersebut berguna bagi konverter untuk merender hasil. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Kadang karena beberapa alasan pemuatan tidak boleh terjadi melalui kode khusus. Dalam kasus tersebut, harap setel flag ini ke True. Dalam kasus ini konverter akan mencoba menggunakan pemuat sumber daya default internal untuk mendapatkan hasil tersebut (seperti perilakunya ketika strategi khusus tidak disediakan). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Kadang pengetahuan tentang tipe MIME sumber daya yang dimuat berguna bagi konverter. Anda dapat menyediakan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Harap biarkan parameter bernilai null ketika tipe MIME tidak diketahui atau tidak perlu disediakan. |

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


