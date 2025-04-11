---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengubah penyimpanan vektor yang ada secara asinkron
type: docs
weight: 430
url: /id/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## Metode OpenAIClient.ModifyVectorStoreAsync

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
| [AIClientException](../../aiclientexception/) | Dilemparkan ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreResponse](../../vectorstoreresponse/)
* kelas [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)