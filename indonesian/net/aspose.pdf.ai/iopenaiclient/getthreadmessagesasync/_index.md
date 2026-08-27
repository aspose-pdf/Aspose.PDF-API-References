---
title: "IOpenAIClient.GetThreadMessagesAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "IOpenAIClient metode. Mengambil daftar pesan untuk thread tertentu secara asinkron"
type: docs
weight: 290
url: /id/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## IOpenAIClient.GetThreadMessagesAsync method

Mengambil daftar pesan untuk thread tertentu secara asynchronous.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread untuk mengambil pesan darinya. |
| queryParameters | ThreadMessageListQueryParameters | Parameter kueri opsional untuk memfilter daftar pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar pesan thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |

### Lihat Juga

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


