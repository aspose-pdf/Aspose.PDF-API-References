---
title: "IOpenAIClient.DeleteVectorStoreAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Menghapus toko vektor secara asinkron"
type: docs
weight: 170
url: /id/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## IOpenAIClient.DeleteVectorStoreAsync method

Menghapus vector store secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID vector store yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi status operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID vector store null atau kosong. |

### Lihat Juga

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


