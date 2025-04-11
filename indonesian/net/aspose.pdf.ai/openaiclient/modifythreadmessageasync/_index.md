---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengubah pesan yang ada dalam sebuah thread secara asinkron
type: docs
weight: 420
url: /id/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## Metode OpenAIClient.ModifyThreadMessageAsync

Mengubah pesan yang ada dalam sebuah thread secara asinkron.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi pesan untuk diubah. |
| threadMessageId | String | ID dari pesan yang akan diubah. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Detail permintaan untuk mengubah pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi pesan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread message Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadMessageResponse](../../threadmessageresponse/)
* kelas [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)