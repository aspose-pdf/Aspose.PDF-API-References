---
title: OpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil detail dari file tertentu dalam penyimpanan vektor secara asinkron
type: docs
weight: 340
url: /id/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## Metode OpenAIClient.GetVectorStoreFileAsync

Mengambil detail dari file tertentu dalam penyimpanan vektor secara asinkron.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang berisi file. |
| fileId | String | ID dari file yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi detail dari file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID file adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileResponse](../../vectorstorefileresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)