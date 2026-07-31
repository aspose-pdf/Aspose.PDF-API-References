---
title: "IOpenAIClient.GetRunAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Mengambil detail run tertentu dalam thread secara asinkron"
type: docs
weight: 230
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync method

Mengambil detail run tertentu dalam thread secara asinkron.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID run yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi detail run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID run null atau kosong. |

### Lihat Juga

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


