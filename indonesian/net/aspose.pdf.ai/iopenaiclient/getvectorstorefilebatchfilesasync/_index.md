---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar file dalam batch file penyimpanan vektor tertentu secara asinkron
type: docs
weight: 330
url: /id/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## Metode IOpenAIClient.GetVectorStoreFileBatchFilesAsync

Mengambil daftar file dalam batch file penyimpanan vektor tertentu secara asinkron.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vectorStoreId | String | ID dari penyimpanan vektor yang berisi batch file. |
| fileBatchId | String | ID dari batch file untuk mengambil file. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Parameter kueri opsional untuk memfilter daftar file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar file dalam batch file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID penyimpanan vektor adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID batch file penyimpanan vektor adalah null atau kosong. |

### Lihat Juga

* kelas [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* kelas [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)