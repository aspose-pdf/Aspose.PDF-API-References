---
title: "OpenAIClient.GetThreadAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Mengambil detail thread tertentu secara asinkron"
type: docs
weight: 310
url: /id/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## OpenAIClient.GetThreadAsync method

Mengambil detail thread tertentu secara asynchronous.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread yang akan diambil. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi detail thread.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |

### Lihat Juga

* class [ThreadResponse](../../threadresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


