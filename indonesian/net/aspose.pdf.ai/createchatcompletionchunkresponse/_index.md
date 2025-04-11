---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Mewakili sebuah chunk yang dialirkan dari respons penyelesaian obrolan yang dikembalikan oleh model berdasarkan input yang diberikan
type: docs
weight: 250
url: /id/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Kelas CreateChatCompletionChunkResponse

Mewakili sebuah chunk yang dialirkan dari respons penyelesaian obrolan yang dikembalikan oleh model, berdasarkan input yang diberikan.

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
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Mengambil atau menetapkan daftar pilihan penyelesaian obrolan. Dapat berisi lebih dari satu elemen jika n lebih besar dari 1. Juga bisa kosong untuk chunk terakhir jika Anda mengatur stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Mengambil atau menetapkan timestamp Unix (dalam detik) ketika penyelesaian obrolan dibuat. Setiap chunk memiliki timestamp yang sama. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Mengambil atau menetapkan pengidentifikasi unik untuk penyelesaian obrolan. Setiap chunk memiliki ID yang sama. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Mengambil atau menetapkan model untuk menghasilkan penyelesaian. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Mengambil atau menetapkan tipe objek, yang selalu chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Mengambil atau menetapkan sidik jari yang mewakili konfigurasi backend yang dijalankan oleh model. Dapat digunakan bersamaan dengan parameter permintaan seed untuk memahami kapan perubahan backend telah dilakukan yang mungkin mempengaruhi determinisme. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Mengambil atau menetapkan bidang opsional yang hanya akan ada ketika Anda mengatur stream_options: {"include_usage": true} dalam permintaan Anda. Ketika ada, ini berisi nilai null kecuali untuk chunk terakhir yang berisi statistik penggunaan token untuk seluruh permintaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)