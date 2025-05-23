---
title: IOpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IOpenAIClient. Mengambil daftar run untuk thread yang ditentukan secara asinkron
type: docs
weight: 240
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## Metode IOpenAIClient.GetRunsAsync

Mengambil daftar run untuk thread yang ditentukan secara asinkron.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread untuk mengambil run. |
| queryParameters | RunListQueryParameters | Parameter kueri opsional untuk memfilter daftar run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunListResponse](../../runlistresponse/)
* kelas [RunListQueryParameters](../../runlistqueryparameters/)
* antarmuka [IOpenAIClient](../)
* ruang nama [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)