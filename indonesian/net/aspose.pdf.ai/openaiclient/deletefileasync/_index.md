---
title: OpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Menghapus file tertentu secara asinkron
type: docs
weight: 140
url: /id/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## Metode OpenAIClient.DeleteFileAsync

Menghapus file tertentu secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileId | String | ID file yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID file adalah null atau kosong. |

### Lihat Juga

* kelas [DeleteStatusResponse](../../deletestatusresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)