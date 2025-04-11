---
title: IOpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Menghapus thread yang ada secara asinkron
type: docs
weight: 150
url: /id/net/aspose.pdf.ai/iopenaiclient/deletethreadasync/
---
## Metode IOpenAIClient.DeleteThreadAsync

Menghapus thread yang ada secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi status dari operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [DeleteStatusResponse](../../deletestatusresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)