---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menunggu penyelesaian sebuah run dalam sebuah thread secara asinkron
type: docs
weight: 440
url: /id/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## Metode IOpenAIClient.WaitForRunToCompleteAsync

Menunggu penyelesaian sebuah run dalam sebuah thread secara asinkron.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID dari run yang akan dipantau hingga selesai. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status akhir dari run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunResponse](../../runresponse/)
* antarmuka [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)