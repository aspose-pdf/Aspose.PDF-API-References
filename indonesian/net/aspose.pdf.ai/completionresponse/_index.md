---
title: "Kelas CompletionResponse"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.CompletionResponse. Mewakili respons penyelesaian obrolan yang dikembalikan oleh model berdasarkan input yang diberikan."
type: docs
weight: 250
url: /id/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

Mewakili respons penyelesaian obrolan yang dikembalikan oleh model, berdasarkan input yang diberikan.

```csharp
public class CompletionResponse : BaseResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Mendapatkan atau mengatur daftar pilihan penyelesaian obrolan. Bisa lebih dari satu jika n lebih besar dari 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Mendapatkan atau mengatur cap waktu Unix (dalam detik) saat penyelesaian obrolan dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik untuk penyelesaian obrolan. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Mendapatkan atau mengatur model yang digunakan untuk penyelesaian obrolan. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Mendapatkan atau mengatur sidik jari yang mewakili konfigurasi backend yang dijalankan oleh model. Dapat digunakan bersama parameter permintaan seed untuk memahami kapan perubahan backend telah dilakukan yang mungkin memengaruhi determinisme. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Mendapatkan atau mengatur statistik penggunaan untuk permintaan penyelesaian. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Mengembalikan konten pilihan pertama sebagai string. |

### Lihat Juga

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


