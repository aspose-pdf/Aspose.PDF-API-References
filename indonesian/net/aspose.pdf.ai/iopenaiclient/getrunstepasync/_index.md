---
title: "IOpenAIClient.GetRunStepAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "IOpenAIClient metode. Mengambil detail langkah tertentu dalam run secara asinkron"
type: docs
weight: 250
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync method

Mengambil detail langkah tertentu dalam sebuah run secara asynchronous.

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

### Nilai Kembalian

Task yang mewakili operasi asynchronous. Hasil task berisi detail dari langkah run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID run null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID langkah run null atau kosong. |

### Lihat Juga

* class [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


