---
title: IOpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membatalkan run yang ada dalam sebuah thread secara asinkron
type: docs
weight: 10
url: /id/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## Metode IOpenAIClient.CancelRunAsync

Membatalkan run yang ada dalam sebuah thread secara asinkron.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run yang akan dibatalkan. |
| runId | String | ID dari run yang akan dibatalkan. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembatalan run.

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