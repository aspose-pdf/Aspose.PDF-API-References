---
title: "IOpenAIClient.CreateRunAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Membuat run dalam thread yang ditentukan secara asinkron"
type: docs
weight: 50
url: /id/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync method

Membuat run dalam thread yang ditentukan secara asinkron.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread tempat run akan dibuat. |
| runCreateRequest | RunCreateRequest | Detail permintaan untuk membuat run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |

### Lihat Juga

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


