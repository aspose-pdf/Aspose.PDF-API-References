---
title: "IOpenAIClient.GetThreadMessageAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Mengambil detail pesan tertentu dalam thread secara asinkron"
type: docs
weight: 280
url: /id/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## IOpenAIClient.GetThreadMessageAsync method

Mengambil detail pesan tertentu dalam sebuah thread secara asynchronous.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi pesan. |
| threadMessageId | String | ID pesan yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi detail pesan thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID pesan thread null atau kosong. |

### Lihat Juga

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


