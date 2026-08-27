---
title: "OpenAIClient.ModifyThreadMessageAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Memodifikasi pesan yang ada dalam thread secara asinkron."
type: docs
weight: 430
url: /id/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync method

Memodifikasi pesan yang ada dalam thread secara asynchronous.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread yang berisi pesan yang akan dimodifikasi. |
| threadMessageId | String | ID pesan yang akan dimodifikasi. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | Detail permintaan untuk memodifikasi pesan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi pesan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID pesan thread null atau kosong. |

### Lihat Juga

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


