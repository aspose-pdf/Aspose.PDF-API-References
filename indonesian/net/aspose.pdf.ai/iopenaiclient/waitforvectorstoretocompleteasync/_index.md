---
title: IOpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menunggu penyelesaian penyimpanan vektor tertentu secara asinkron
type: docs
weight: 470
url: /id/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## Metode IOpenAIClient.WaitForVectorStoreToCompleteAsync

Menunggu penyimpanan vektor tertentu untuk menyelesaikan secara asinkron.

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
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)