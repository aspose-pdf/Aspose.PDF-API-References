---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.LlamaChatCompletionResponse. Mewakili respons penyelesaian obrolan yang dikembalikan oleh model berdasarkan input yang diberikan
type: docs
weight: 690
url: /id/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## Kelas LlamaChatCompletionResponse

Mewakili respons penyelesaian obrolan yang dikembalikan oleh model, berdasarkan input yang diberikan.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Mendapatkan atau mengatur daftar pilihan penyelesaian obrolan. Bisa lebih dari satu jika n lebih besar dari 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) saat penyelesaian obrolan dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik untuk penyelesaian obrolan. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Mendapatkan atau mengatur model yang digunakan untuk penyelesaian obrolan. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Mendapatkan atau mengatur sidik jari yang mewakili konfigurasi backend yang dijalankan model. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan untuk permintaan penyelesaian. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Mengembalikan representasi string dari pilihan pertama. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)