---
title: "Kelas ThreadMessageResponse"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.ThreadMessageResponse. Mewakili sebuah pesan dalam sebuah thread"
type: docs
weight: 1250
url: /id/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

Mewakili pesan dalam sebuah thread.

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
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Mendapatkan atau mengatur, jika berlaku, ID asisten yang menulis pesan ini. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Mendapatkan atau mengatur daftar file yang dilampirkan pada pesan. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Mendapatkan atau mengatur cap waktu Unix (dalam detik) saat pesan selesai. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Mendapatkan atau mengatur konten pesan dalam sebuah array teks dan/atau gambar. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Mendapatkan atau mengatur cap waktu Unix (dalam detik) saat pesan dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi, yang dapat direferensikan dalam endpoint API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Mendapatkan atau mengatur cap waktu Unix (dalam detik) saat pesan ditandai tidak lengkap. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Mendapatkan atau mengatur pesan tidak lengkap, detail mengapa pesan tidak lengkap. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan ke sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Mendapatkan atau mengatur entitas yang menghasilkan pesan. Salah satu dari "user" atau "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Mendapatkan atau mengatur ID run yang terkait dengan pembuatan pesan ini. Nilai null ketika pesan dibuat secara manual. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Mendapatkan atau mengatur status pesan. Salah satu dari queued, in_progress, requires_action, atau completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Mendapatkan atau mengatur ID thread tempat pesan ini berada. |

### Lihat Juga

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


