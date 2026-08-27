---
title: "IOpenAIClient.ModifyVectorStoreAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode IOpenAIClient. Memodifikasi vector store yang ada secara asinkron"
type: docs
weight: 400
url: /id/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync method

Memodifikasi vector store yang ada secara asynchronous.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID vector store yang akan dimodifikasi. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | Objek permintaan yang berisi detail modifikasi. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Task yang mewakili operasi asinkron. Hasil task berisi respons dari modifikasi vector store.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID vector store null atau kosong. |

### Lihat Juga

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


