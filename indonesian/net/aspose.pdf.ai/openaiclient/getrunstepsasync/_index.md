---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil daftar langkah untuk run tertentu dalam sebuah thread secara asinkron
type: docs
weight: 280
url: /id/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## Metode OpenAIClient.GetRunStepsAsync

Mengambil daftar langkah untuk run tertentu dalam sebuah thread secara asinkron.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID dari run untuk mengambil langkah-langkah. |
| queryParameters | RunStepListQueryParameters | Parameter kueri opsional untuk memfilter daftar langkah run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar langkah run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunStepListResponse](../../runsteplistresponse/)
* kelas [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)