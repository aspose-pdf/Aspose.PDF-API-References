---
title: OpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil rincian langkah tertentu dalam sebuah run secara asinkron
type: docs
weight: 270
url: /id/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## Metode OpenAIClient.GetRunStepAsync

Mengambil rincian langkah tertentu dalam sebuah run secara asinkron.

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

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi rincian dari langkah run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run step Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunStepResponse](../../runstepresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)