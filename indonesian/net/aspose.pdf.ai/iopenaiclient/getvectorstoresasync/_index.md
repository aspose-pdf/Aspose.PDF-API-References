---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Mengambil daftar vector store secara asinkron"
type: docs
weight: 350
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync method

Mengambil daftar vector store secara asynchronous.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | Parameter kueri opsional untuk menyaring daftar vector store. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar penyimpanan vektor.

### Lihat Juga

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


