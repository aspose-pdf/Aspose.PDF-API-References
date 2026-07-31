---
title: "Kelas CreateChatCompletionChunkResponse"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Mewakili potongan aliran dari respons penyelesaian obrolan yang dikembalikan oleh model berdasarkan input yang diberikan."
type: docs
weight: 260
url: /id/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

Mewakili potongan aliran dari respons penyelesaian obrolan yang dikembalikan oleh model, berdasarkan input yang diberikan.

```csharp
public class CreateChatCompletionChunkResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Mendapatkan atau mengatur daftar pilihan penyelesaian obrolan. Dapat berisi lebih dari satu elemen jika n lebih besar dari 1. Juga dapat kosong untuk potongan terakhir jika Anda mengatur stream_options: {\"include_usage\": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Mendapatkan atau mengatur stempel waktu Unix (dalam detik) saat penyelesaian obrolan dibuat. Setiap potongan memiliki stempel waktu yang sama. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik untuk penyelesaian obrolan. Setiap potongan memiliki ID yang sama. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Mendapatkan atau mengatur model untuk menghasilkan penyelesaian. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Mendapatkan atau mengatur sidik jari yang mewakili konfigurasi backend yang dijalankan oleh model. Dapat digunakan bersama parameter permintaan seed untuk memahami kapan perubahan backend telah dilakukan yang mungkin memengaruhi determinisme. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Mendapatkan atau mengatur bidang opsional yang hanya akan ada ketika Anda mengatur stream_options: {"include_usage": true} dalam permintaan Anda. Ketika ada, ia berisi nilai null kecuali untuk bagian terakhir yang berisi statistik penggunaan token untuk seluruh permintaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


