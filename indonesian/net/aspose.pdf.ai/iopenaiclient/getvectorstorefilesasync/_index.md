---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar file dalam penyimpanan vektor tertentu secara asinkron
type: docs
weight: 340
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## Metode IOpenAIClient.GetVectorStoreFilesAsync

Mengambil daftar file dalam penyimpanan vektor tertentu secara asinkron.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang berisi file. |
| queryParameters | VectorStoreFileListQueryParameters | Parameter kueri opsional untuk memfilter daftar file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar file dalam penyimpanan vektor.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* kelas [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)