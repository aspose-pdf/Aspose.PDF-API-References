---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.RunStepResponse. Mewakili sebuah langkah dalam eksekusi sebuah run
type: docs
weight: 1060
url: /id/net/aspose.pdf.ai/runstepresponse/
---
## Kelas RunStepResponse

Mewakili sebuah langkah dalam eksekusi sebuah run.

```csharp
public class RunStepResponse : BaseResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Mendapatkan atau mengatur ID asisten yang terkait dengan langkah run. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat langkah run dibatalkan. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat langkah run selesai. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat langkah run dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat langkah run kedaluwarsa. Sebuah langkah dianggap kedaluwarsa jika run induknya kedaluwarsa. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat langkah run gagal. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi langkah run, yang dapat dirujuk dalam endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Mendapatkan atau mengatur kesalahan terakhir yang terkait dengan langkah run ini. Akan bernilai null jika tidak ada kesalahan. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Mendapatkan atau mengatur ID run yang merupakan bagian dari langkah run ini. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Mendapatkan atau mengatur tipe langkah run, yang dapat berupa message_creation atau tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Mendapatkan atau mengatur status langkah run, yang dapat berupa in_progress, cancelled, failed, completed, atau expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Mendapatkan atau mengatur detail langkah run. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Mendapatkan atau mengatur ID thread yang dijalankan. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan terkait dengan langkah run. Nilai ini akan bernilai null saat status langkah run adalah in_progress. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)