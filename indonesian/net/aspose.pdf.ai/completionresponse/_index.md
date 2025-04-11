---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.CompletionResponse. Mewakili respons penyelesaian obrolan yang dikembalikan oleh model berdasarkan input yang diberikan
type: docs
weight: 240
url: /id/net/aspose.pdf.ai/completionresponse/
---
## Kelas CompletionResponse

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
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Mengambil atau mengatur daftar pilihan penyelesaian obrolan. Bisa lebih dari satu jika n lebih besar dari 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Mengambil atau mengatur timestamp Unix (dalam detik) saat penyelesaian obrolan dibuat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mengambil atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mengambil atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mengambil atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mengambil atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mengambil atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Mengambil atau mengatur pengidentifikasi unik untuk penyelesaian obrolan. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Mengambil atau mengatur model yang digunakan untuk penyelesaian obrolan. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Mengambil atau mengatur tipe objek, yang selalu chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mengambil frasa alasan kesalahan. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Mengambil atau mengatur sidik jari yang mewakili konfigurasi backend yang dijalankan model. Dapat digunakan bersamaan dengan parameter permintaan seed untuk memahami kapan perubahan backend telah dilakukan yang mungkin mempengaruhi determinisme. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Mengambil atau mengatur statistik penggunaan untuk permintaan penyelesaian. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Mengembalikan konten pilihan pertama sebagai string. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)