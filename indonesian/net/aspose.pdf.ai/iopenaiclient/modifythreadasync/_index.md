---
title: IOpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Memodifikasi thread yang ada secara asinkron
type: docs
weight: 380
url: /id/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## Metode IOpenAIClient.ModifyThreadAsync

Memodifikasi thread yang ada secara asinkron.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang akan dimodifikasi. |
| threadModifyRequest | ThreadModifyRequest | Objek permintaan yang berisi detail modifikasi. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadResponse](../../threadresponse/)
* kelas [ThreadModifyRequest](../../threadmodifyrequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)