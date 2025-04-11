---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat thread baru secara asinkron
type: docs
weight: 70
url: /id/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## Metode IOpenAIClient.CreateThreadAsync

Membuat thread baru secara asinkron.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | Objek permintaan yang berisi detail untuk membuat thread. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan thread.

### Lihat Juga

* kelas [ThreadResponse](../../threadresponse/)
* kelas [ThreadCreateRequest](../../threadcreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)