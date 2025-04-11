---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil rincian asisten tertentu secara asinkron
type: docs
weight: 190
url: /id/net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## Metode IOpenAIClient.GetAssistantAsync

Mengambil rincian asisten tertentu secara asinkron.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantId | String | ID asisten yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi rincian asisten.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilemparkan ketika ID asisten adalah null atau kosong. |

### Lihat Juga

* kelas [AssistantResponse](../../assistantresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)