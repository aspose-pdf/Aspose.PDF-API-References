---
title: IOpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menghapus file tertentu secara asinkron
type: docs
weight: 140
url: /id/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## Metode IOpenAIClient.DeleteFileAsync

Menghapus file tertentu secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileId | String | ID dari file yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status dari operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID file adalah null atau kosong. |

### Lihat Juga

* kelas [DeleteStatusResponse](../../deletestatusresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)