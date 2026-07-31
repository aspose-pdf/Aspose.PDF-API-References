---
title: "OpenAIClient.DeleteAssistantAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Menghapus asisten yang ada secara asinkron"
type: docs
weight: 130
url: /id/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## OpenAIClient.DeleteAssistantAsync method

Menghapus asisten yang ada secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assistantId | String | ID asisten yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi status operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika Id asisten bernilai null atau kosong. |

### Lihat Juga

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


