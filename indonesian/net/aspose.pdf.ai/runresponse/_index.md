---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.RunResponse. Mewakili eksekusi yang berjalan pada sebuah thread
type: docs
weight: 1020
url: /id/net/aspose.pdf.ai/runresponse/
---
## Kelas RunResponse

Mewakili eksekusi yang berjalan pada sebuah thread.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RunResponse](runresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Mendapatkan atau menetapkan ID asisten yang digunakan untuk eksekusi run ini. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run dibatalkan. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run diselesaikan. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau menetapkan detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau menetapkan kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau menetapkan informasi kesalahan. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run akan kedaluwarsa. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run gagal. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau menetapkan header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau menetapkan kode status HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Mendapatkan atau menetapkan pengidentifikasi, yang dapat dirujuk dalam endpoint API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Mendapatkan atau menetapkan detail mengapa run tidak lengkap. Akan bernilai null jika run tidak tidak lengkap. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Mendapatkan atau menetapkan instruksi yang digunakan asisten untuk run ini. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Mendapatkan atau menetapkan kesalahan terakhir yang terkait dengan run ini. Akan bernilai null jika tidak ada kesalahan. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token penyelesaian yang ditentukan telah digunakan selama run. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token prompt yang ditentukan telah digunakan selama run. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Mendapatkan atau menetapkan model yang digunakan asisten untuk run ini. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Mendapatkan atau menetapkan tipe objek, yang selalu thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Mendapatkan atau menetapkan detail tentang tindakan yang diperlukan untuk melanjutkan run. Akan bernilai null jika tidak ada tindakan yang diperlukan. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Mendapatkan atau menetapkan format yang harus dihasilkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { "type": "json_object" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi yang tidak berujung sampai generasi mencapai batas token, yang mengakibatkan permintaan yang berjalan lama dan tampaknya "terjebak". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason="length", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Mendapatkan atau menetapkan timestamp Unix (dalam detik) untuk saat run dimulai. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Mendapatkan atau menetapkan status run, yang dapat berupa queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete, atau expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Mendapatkan atau menetapkan suhu pengambilan sampel yang digunakan untuk run ini. Jika tidak diatur, defaultnya adalah 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Mendapatkan atau menetapkan ID thread yang dieksekusi sebagai bagian dari run ini. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Mendapatkan atau menetapkan alat mana (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {"type": "file_search"} atau {"type": "function", "function": {"name": "my_function"}} memaksa model untuk memanggil alat tersebut. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Mendapatkan atau menetapkan daftar alat yang digunakan asisten untuk run ini. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Mendapatkan atau menetapkan nilai pengambilan sampel nucleus yang digunakan untuk run ini. Jika tidak diatur, defaultnya adalah 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Mendapatkan atau menetapkan strategi pemotongan yang mengontrol bagaimana sebuah thread akan dipotong sebelum run. Gunakan ini untuk mengontrol jendela konteks awal dari run. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Mendapatkan atau menetapkan statistik penggunaan yang terkait dengan run. Nilai ini akan bernilai null jika run tidak dalam keadaan terminal (misalnya in_progress, queued, dll.). |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* antarmuka [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)