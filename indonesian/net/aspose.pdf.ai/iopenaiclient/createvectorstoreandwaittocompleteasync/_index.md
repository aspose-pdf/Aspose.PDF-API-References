---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat penyimpanan vektor baru dan menunggu hingga selesai secara asinkron
type: docs
weight: 90
url: /id/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## Metode IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

Membuat penyimpanan vektor baru dan menunggu hingga selesai secara asinkron.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Objek permintaan yang berisi rincian untuk membuat penyimpanan vektor. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan penyimpanan vektor setelah selesai.

### Lihat Juga

* kelas [VectorStoreResponse](../../vectorstoreresponse/)
* kelas [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)