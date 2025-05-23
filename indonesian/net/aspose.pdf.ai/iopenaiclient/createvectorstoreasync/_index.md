---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Membuat penyimpanan vektor baru secara asinkron
type: docs
weight: 100
url: /id/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## Metode IOpenAIClient.CreateVectorStoreAsync

Membuat penyimpanan vektor baru secara asinkron.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Objek permintaan yang berisi detail untuk membuat penyimpanan vektor. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan penyimpanan vektor.

### Lihat Juga

* kelas [VectorStoreResponse](../../vectorstoreresponse/)
* kelas [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)