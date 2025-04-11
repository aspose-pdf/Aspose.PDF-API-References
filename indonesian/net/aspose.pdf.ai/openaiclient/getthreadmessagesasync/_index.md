---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil daftar pesan untuk thread tertentu secara asinkron
type: docs
weight: 320
url: /id/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## Metode OpenAIClient.GetThreadMessagesAsync

Mengambil daftar pesan untuk thread tertentu secara asinkron.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread untuk mengambil pesan. |
| queryParameters | ThreadMessageListQueryParameters | Parameter kueri opsional untuk memfilter daftar pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar pesan thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadMessageListResponse](../../threadmessagelistresponse/)
* kelas [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)