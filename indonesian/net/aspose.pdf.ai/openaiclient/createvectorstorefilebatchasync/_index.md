---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Membuat batch file penyimpanan vektor baru secara asinkron
type: docs
weight: 120
url: /id/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## Metode OpenAIClient.CreateVectorStoreFileBatchAsync

Membuat batch file penyimpanan vektor baru secara asinkron.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor tempat batch file akan dibuat. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | Objek permintaan yang berisi detail untuk membuat batch file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan batch file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* kelas [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)