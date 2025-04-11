---
title: OpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Menunggu agar penyimpanan vektor tertentu selesai secara asinkron
type: docs
weight: 500
url: /id/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## Metode OpenAIClient.WaitForVectorStoreToCompleteAsync

Menunggu agar penyimpanan vektor tertentu selesai secara asinkron.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang akan dipantau hingga selesai. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status akhir dari penyimpanan vektor.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreResponse](../../vectorstoreresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)