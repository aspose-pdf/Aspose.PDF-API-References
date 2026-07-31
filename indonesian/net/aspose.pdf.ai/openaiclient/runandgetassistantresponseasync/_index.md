---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Menjalankan asisten dengan threadId dan runCreateRequest yang ditentukan serta secara asinkron mendapatkan respons asisten"
type: docs
weight: 450
url: /id/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


