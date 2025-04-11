---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat sebuah thread dan menjalankannya secara asinkron
type: docs
weight: 60
url: /id/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## Metode IOpenAIClient.CreateThreadAndRunAsync

Membuat sebuah thread dan menjalankannya secara asinkron.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Detail permintaan untuk membuat thread dan run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan thread dan run.

### Lihat Juga

* kelas [RunResponse](../../runresponse/)
* kelas [RunThreadCreateRequest](../../runthreadcreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)