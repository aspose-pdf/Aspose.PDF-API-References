---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Memodifikasi pesan yang ada dalam sebuah thread secara asinkron
type: docs
weight: 390
url: /id/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## Metode IOpenAIClient.ModifyThreadMessageAsync

Memodifikasi pesan yang ada dalam sebuah thread secara asinkron.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi pesan untuk dimodifikasi. |
| threadMessageId | String | ID dari pesan yang akan dimodifikasi. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Detail permintaan untuk memodifikasi pesan. |
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
* antarmuka [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)