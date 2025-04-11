---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengambil detail dari file tertentu secara asinkron
type: docs
weight: 220
url: /id/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## Metode OpenAIClient.GetFileAsync

Mengambil detail dari file tertentu secara asinkron.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileId | String | ID dari file yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi detail dari file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika file Id adalah null atau kosong. |

### Lihat Juga

* kelas [FileResponse](../../fileresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)