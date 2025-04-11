---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.ThreadResponse. Mewakili sebuah thread yang berisi pesan
type: docs
weight: 1180
url: /id/net/aspose.pdf.ai/threadresponse/
---
## Kelas ThreadResponse

Mewakili sebuah thread yang berisi pesan.

```csharp
public class ThreadResponse : BaseResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat thread dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau menetapkan detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau menetapkan kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau menetapkan informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau menetapkan header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau menetapkan kode status HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Mendapatkan atau menetapkan pengidentifikasi, yang dapat dirujuk dalam endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Mendapatkan atau menetapkan tipe objek, yang selalu berupa thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Mendapatkan atau menetapkan sekumpulan sumber daya yang tersedia untuk alat asisten dalam thread ini. Sumber daya spesifik untuk jenis alat. Misalnya, alat code_interpreter memerlukan daftar ID file, sementara alat file_search memerlukan daftar ID penyimpanan vektor. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)