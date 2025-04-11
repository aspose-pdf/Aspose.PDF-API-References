---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar asisten secara asinkron
type: docs
weight: 200
url: /id/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## Metode IOpenAIClient.GetAssistantsAsync

Mengambil daftar asisten secara asinkron.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Parameter kueri opsional untuk memfilter daftar asisten. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar asisten.

### Lihat Juga

* kelas [AssistantListResponse](../../assistantlistresponse/)
* kelas [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)