---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menjalankan asisten dengan threadId yang ditentukan dan runCreateRequest dan secara asinkron mendapatkan respons asisten
type: docs
weight: 410
url: /id/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## Metode IOpenAIClient.RunAndGetAssistantResponseAsync

Menjalankan asisten dengan threadId yang ditentukan dan runCreateRequest, dan secara asinkron mendapatkan respons asisten.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread. |
| runCreateRequest | RunCreateRequest | Permintaan pembuatan run. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron dengan string respons asisten.

### Lihat Juga

* kelas [RunCreateRequest](../../runcreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)