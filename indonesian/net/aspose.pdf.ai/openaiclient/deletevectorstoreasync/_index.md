---
title: OpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Menghapus penyimpanan vektor secara asinkron
type: docs
weight: 170
url: /id/net/aspose.pdf.ai/openaiclient/deletevectorstoreasync/
---
## Metode OpenAIClient.DeleteVectorStoreAsync

Menghapus penyimpanan vektor secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status dari operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [DeleteStatusResponse](../../deletestatusresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)