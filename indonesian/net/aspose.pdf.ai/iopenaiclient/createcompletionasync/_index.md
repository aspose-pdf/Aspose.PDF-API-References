---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat penyelesaian baru secara asinkron
type: docs
weight: 40
url: /id/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## Metode IOpenAIClient.CreateCompletionAsync

Membuat penyelesaian baru secara asinkron.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | Objek permintaan yang berisi detail untuk membuat penyelesaian. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan penyelesaian.

### Lihat Juga

* kelas [CompletionResponse](../../completionresponse/)
* kelas [CompletionCreateRequest](../../completioncreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)