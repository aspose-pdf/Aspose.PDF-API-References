---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.ThreadMessageResponse. Mewakili sebuah pesan dalam sebuah thread
type: docs
weight: 1160
url: /id/net/aspose.pdf.ai/threadmessageresponse/
---
## Kelas ThreadMessageResponse

Mewakili sebuah pesan dalam sebuah thread.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Mendapatkan atau menetapkan, jika berlaku, ID asisten yang menulis pesan ini. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Mendapatkan atau menetapkan daftar file yang dilampirkan pada pesan. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat pesan diselesaikan. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Mendapatkan atau menetapkan konten pesan dalam array teks dan/atau gambar. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat pesan dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau menetapkan detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau menetapkan kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau menetapkan informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau menetapkan header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau menetapkan kode status HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Mendapatkan atau menetapkan pengidentifikasi, yang dapat dirujuk dalam endpoint API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat pesan ditandai sebagai tidak lengkap. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Mendapatkan atau menetapkan pesan yang tidak lengkap, detail tentang mengapa pesan tersebut tidak lengkap. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Mendapatkan atau menetapkan tipe objek, yang selalu "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Mendapatkan atau menetapkan entitas yang menghasilkan pesan. Salah satu dari "user" atau "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Mendapatkan atau menetapkan ID dari run yang terkait dengan pembuatan pesan ini. Nilai adalah null ketika pesan dibuat secara manual. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Mendapatkan atau menetapkan status pesan. Salah satu dari queued, in_progress, requires_action, atau completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Mendapatkan atau menetapkan ID dari thread yang menjadi milik pesan ini. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* antarmuka [IStatus](../istatus/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)