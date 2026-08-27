---
title: "Kelas RunResponse"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.RunResponse. Mewakili eksekusi run pada sebuah thread"
type: docs
weight: 1100
url: /id/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

Mewakili eksekusi run pada thread.

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
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Mendapatkan atau mengatur ID asisten yang digunakan untuk mengeksekusi run ini. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run dibatalkan. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run selesai. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run akan kedaluwarsa. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run gagal. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi, yang dapat direferensikan dalam endpoint API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Menentukan atau mengatur detail mengapa run tidak lengkap. Akan bernilai null jika run tidak tidak lengkap. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Menentukan atau mengatur instruksi yang digunakan asisten untuk run ini. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Menentukan atau mengatur kesalahan terakhir yang terkait dengan run ini. Akan bernilai null jika tidak ada kesalahan. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Menentukan atau mengatur jumlah maksimum token penyelesaian yang ditentukan telah digunakan selama run. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Menentukan atau mengatur jumlah maksimum token prompt yang ditentukan telah digunakan selama run. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan ke sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Menentukan atau mengatur model yang digunakan asisten untuk run ini. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Menentukan atau mengatur tipe objek, yang selalu thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Menentukan atau mengatur detail tindakan yang diperlukan untuk melanjutkan run. Akan bernilai null jika tidak ada tindakan yang diperlukan. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Menentukan atau mengatur format yang harus dikeluarkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi tak berujung hingga generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak \"macet\". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason=\"length\", yang menunjukkan generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Menentukan atau mengatur cap waktu Unix (dalam detik) saat run dimulai. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Menentukan atau mengatur status run, yang dapat berupa queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete, atau expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Menentukan atau mengatur suhu sampling yang digunakan untuk run ini. Jika tidak diatur, defaultnya 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Menentukan atau mengatur ID thread yang dieksekusi sebagai bagian dari run ini. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Menentukan atau mengatur alat (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan malah menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {\"type\": \"file_search\"} atau {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} memaksa model untuk memanggil alat tersebut. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Menentukan atau mengatur daftar alat yang digunakan asisten untuk run ini. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Menentukan atau mengatur nilai nucleus sampling yang digunakan untuk run ini. Jika tidak diatur, defaultnya 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Mendapatkan atau mengatur strategi pemotongan yang mengontrol bagaimana thread akan dipotong sebelum run. Gunakan ini untuk mengontrol jendela konteks awal run. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan yang terkait dengan run. Nilai ini akan null jika run tidak berada dalam status terminal (misalnya in_progress, queued, dll.). |

### Lihat Juga

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


