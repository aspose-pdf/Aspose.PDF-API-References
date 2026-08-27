---
title: "IOpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Menjalankan asisten dengan threadId yang ditentukan dan runCreateRequest serta secara asinkron mendapatkan respons asisten"
type: docs
weight: 410
url: /id/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync method

Menjalankan assistant dengan threadId dan runCreateRequest yang ditentukan, dan secara asynchronous mendapatkan respons assistant.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread. |
| runCreateRequest | RunCreateRequest | Permintaan pembuatan run. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi asinkron dengan string respons asisten.

### Lihat Juga

* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


