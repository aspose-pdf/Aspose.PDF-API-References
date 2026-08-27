---
title: "IOpenAIClient.ModifyAssistantAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "IOpenAIClient metode. Memodifikasi asisten yang ada secara asinkron"
type: docs
weight: 360
url: /id/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync method

Memodifikasi assistant yang ada secara asynchronous.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantId | String | ID asisten yang akan dimodifikasi. |
| assistantModifyRequest | AssistantModifyRequest | Objek permintaan yang berisi detail modifikasi. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi asisten.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika Id asisten bernilai null atau kosong. |

### Lihat Juga

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


