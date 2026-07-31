---
title: "OpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Menunggu sebuah vector store tertentu selesai secara asinkron."
type: docs
weight: 510
url: /id/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## OpenAIClient.WaitForVectorStoreToCompleteAsync method

Menunggu vector store tertentu selesai secara asynchronous.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID vector store yang dipantau hingga selesai. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi status akhir dari vector store.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID vector store null atau kosong. |

### Lihat Juga

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


