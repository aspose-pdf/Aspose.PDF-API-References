---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar pesan untuk thread tertentu secara asinkron
type: docs
weight: 290
url: /id/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## Metode IOpenAIClient.GetThreadMessagesAsync

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
* antarmuka [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)