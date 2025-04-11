---
title: OpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Menunggu pesan pertama dari asisten dalam sebuah thread secara asinkron
type: docs
weight: 460
url: /id/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## Metode OpenAIClient.WaitForAssistantMessageAsync

Menunggu pesan pertama dari asisten dalam sebuah thread secara asinkron.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread untuk memantau pesan pertama dari asisten. |
| queryParameters | ThreadMessageListQueryParameters | Parameter kueri opsional untuk memfilter daftar pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi pesan pertama dari asisten dalam thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadMessageResponse](../../threadmessageresponse/)
* kelas [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)