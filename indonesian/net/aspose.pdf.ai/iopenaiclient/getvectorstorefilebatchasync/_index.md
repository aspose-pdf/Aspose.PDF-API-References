---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil rincian dari batch file penyimpanan vektor tertentu secara asinkron
type: docs
weight: 320
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## Metode IOpenAIClient.GetVectorStoreFileBatchAsync

Mengambil rincian dari batch file penyimpanan vektor tertentu secara asinkron.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang berisi batch file. |
| fileBatchId | String | ID dari batch file yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi rincian dari batch file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID batch file penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)