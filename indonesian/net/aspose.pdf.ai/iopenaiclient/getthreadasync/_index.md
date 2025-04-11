---
title: IOpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil detail dari thread tertentu secara asinkron
type: docs
weight: 270
url: /id/net/aspose.pdf.ai/iopenaiclient/getthreadasync/
---
## Metode IOpenAIClient.GetThreadAsync

Mengambil detail dari thread tertentu secara asinkron.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi detail dari thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilemparkan ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [ThreadResponse](../../threadresponse/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)