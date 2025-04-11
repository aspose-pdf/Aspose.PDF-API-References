---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar file secara asinkron berdasarkan tujuan yang ditentukan
type: docs
weight: 220
url: /id/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## Metode IOpenAIClient.GetFilesAsync

Mengambil daftar file secara asinkron berdasarkan tujuan yang ditentukan.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| purpose | String | Opsional. Tujuan dari file yang akan diambil. Jika null, file untuk semua tujuan akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar file.

### Lihat Juga

* kelas [FileListResponse](../../filelistresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)