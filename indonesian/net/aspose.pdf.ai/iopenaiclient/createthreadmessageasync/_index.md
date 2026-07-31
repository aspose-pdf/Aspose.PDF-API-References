---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Membuat pesan baru dalam thread secara asinkron"
type: docs
weight: 80
url: /id/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

Membuat pesan baru dalam thread secara asinkron.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread tempat pesan akan dibuat. |
| threadMessageRequest | ThreadMessageCreateRequest | Detail permintaan untuk membuat pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan pesan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |

### Lihat Juga

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


