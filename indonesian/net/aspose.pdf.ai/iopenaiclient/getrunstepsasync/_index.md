---
title: "IOpenAIClient.GetRunStepsAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Mengambil daftar langkah untuk run tertentu dalam thread secara asinkron"
type: docs
weight: 260
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

Mengambil daftar langkah untuk run tertentu dalam sebuah thread secara asynchronous.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID run yang akan diambil langkah-langkahnya. |
| queryParameters | RunStepListQueryParameters | Parameter kueri opsional untuk memfilter daftar langkah run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar langkah run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID run null atau kosong. |

### Lihat Juga

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


