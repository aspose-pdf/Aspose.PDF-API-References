---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Membuat file penyimpanan vektor baru secara asinkron
type: docs
weight: 110
url: /id/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## Metode OpenAIClient.CreateVectorStoreFileAsync

Membuat file penyimpanan vektor baru secara asinkron.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor tempat file akan dibuat. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | Objek permintaan yang berisi detail untuk membuat file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pembuatan file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileResponse](../../vectorstorefileresponse/)
* kelas [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)