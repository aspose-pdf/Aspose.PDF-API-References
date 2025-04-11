---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Memodifikasi asisten yang ada secara asinkron
type: docs
weight: 360
url: /id/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## Metode IOpenAIClient.ModifyAssistantAsync

Memodifikasi asisten yang ada secara asinkron.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantId | String | ID asisten yang akan dimodifikasi. |
| assistantModifyRequest | AssistantModifyRequest | Objek permintaan yang berisi detail modifikasi. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi asisten.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID asisten adalah null atau kosong. |

### Lihat Juga

* kelas [AssistantResponse](../../assistantresponse/)
* kelas [AssistantModifyRequest](../../assistantmodifyrequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)