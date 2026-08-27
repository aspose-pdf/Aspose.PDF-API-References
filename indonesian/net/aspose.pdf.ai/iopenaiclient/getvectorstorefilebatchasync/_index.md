---
title: "IOpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Mengambil detail batch file vector store tertentu secara asinkron"
type: docs
weight: 320
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## IOpenAIClient.GetVectorStoreFileBatchAsync method

Mengambil detail batch file vector store tertentu secara asynchronous.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID vector store yang berisi batch file. |
| fileBatchId | String | ID batch file yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi detail dari batch file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID vector store null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID batch file vector store bernilai null atau kosong. |

### Lihat Juga

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


