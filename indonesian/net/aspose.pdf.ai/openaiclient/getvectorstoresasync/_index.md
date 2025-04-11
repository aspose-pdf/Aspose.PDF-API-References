---
title: OpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil daftar penyimpanan vektor secara asinkron
type: docs
weight: 380
url: /id/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## Metode OpenAIClient.GetVectorStoresAsync

Mengambil daftar penyimpanan vektor secara asinkron.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Parameter kueri opsional untuk memfilter daftar penyimpanan vektor. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar penyimpanan vektor.

### Lihat Juga

* kelas [VectorStoreListResponse](../../vectorstorelistresponse/)
* kelas [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)