---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil detail dari langkah tertentu dalam sebuah run secara asinkron
type: docs
weight: 250
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## Metode IOpenAIClient.GetRunStepAsync

Mengambil detail dari langkah tertentu dalam sebuah run secara asinkron.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID dari run yang berisi langkah. |
| runStepId | String | ID dari langkah run yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi detail dari langkah run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run step Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunStepResponse](../../runstepresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)