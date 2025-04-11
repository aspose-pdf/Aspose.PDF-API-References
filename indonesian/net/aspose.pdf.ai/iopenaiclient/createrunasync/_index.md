---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat run dalam thread yang ditentukan secara asinkron
type: docs
weight: 50
url: /id/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## Metode IOpenAIClient.CreateRunAsync

Membuat run dalam thread yang ditentukan secara asinkron.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread tempat run akan dibuat. |
| runCreateRequest | RunCreateRequest | Detail permintaan untuk membuat run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunResponse](../../runresponse/)
* kelas [RunCreateRequest](../../runcreaterequest/)
* antarmuka [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)