---
title: "IOpenAIClient.GetVectorStoreFileAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Mengambil detail file tertentu dalam vector store secara asinkron"
type: docs
weight: 310
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## IOpenAIClient.GetVectorStoreFileAsync method

Mengambil detail file tertentu dalam vector store secara asynchronous.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID vector store yang berisi file. |
| fileId | String | ID file yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Task yang mewakili operasi asinkron. Hasil task berisi detail file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID vector store null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika Id file null atau kosong. |

### Lihat Juga

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


