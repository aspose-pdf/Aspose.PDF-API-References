---
title: OpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Menghapus asisten yang ada secara asinkron
type: docs
weight: 130
url: /id/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## Metode OpenAIClient.DeleteAssistantAsync

Menghapus asisten yang ada secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantId | String | ID asisten yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status dari operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID asisten adalah null atau kosong. |

### Lihat Juga

* kelas [DeleteStatusResponse](../../deletestatusresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)