---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengubah penyimpanan vektor yang ada secara asinkron
type: docs
weight: 400
url: /id/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## Metode IOpenAIClient.ModifyVectorStoreAsync

Mengubah penyimpanan vektor yang ada secara asinkron.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang akan diubah. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Objek permintaan yang berisi detail modifikasi. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi penyimpanan vektor.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreResponse](../../vectorstoreresponse/)
* kelas [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)