---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Membuat pesan baru dalam sebuah thread secara asinkron
type: docs
weight: 80
url: /id/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## Metode OpenAIClient.CreateThreadMessageAsync

Membuat pesan baru dalam sebuah thread secara asinkron.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread tempat pesan akan dibuat. |
| threadMessageRequest | ThreadMessageCreateRequest | Detail permintaan untuk membuat pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan pesan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadMessageResponse](../../threadmessageresponse/)
* kelas [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)