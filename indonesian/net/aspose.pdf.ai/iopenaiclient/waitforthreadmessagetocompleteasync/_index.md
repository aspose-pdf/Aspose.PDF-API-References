---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menunggu pesan thread tertentu untuk selesai secara asinkron
type: docs
weight: 450
url: /id/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## Metode IOpenAIClient.WaitForThreadMessageToCompleteAsync

Menunggu pesan thread tertentu untuk selesai secara asinkron.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi pesan. |
| threadMessageId | String | ID dari pesan yang akan dipantau hingga selesai. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status akhir dari pesan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread message Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadMessageResponse](../../threadmessageresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)