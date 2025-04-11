---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat asisten baru secara asinkron
type: docs
weight: 30
url: /id/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## Metode IOpenAIClient.CreateAssistantAsync

Membuat asisten baru secara asinkron.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | Objek permintaan yang berisi detail untuk membuat asisten. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan asisten.

### Lihat Juga

* kelas [AssistantResponse](../../assistantresponse/)
* kelas [AssistantCreateRequest](../../assistantcreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)