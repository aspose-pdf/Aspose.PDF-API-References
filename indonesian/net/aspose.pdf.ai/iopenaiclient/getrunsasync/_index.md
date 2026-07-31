---
title: "IOpenAIClient.GetRunsAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IOpenAIClient. Mengambil daftar run untuk thread yang ditentukan secara asinkron"
type: docs
weight: 240
url: /id/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## IOpenAIClient.GetRunsAsync method

Mengambil daftar run untuk thread yang ditentukan secara asinkron.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID thread untuk mengambil run. |
| queryParameters | RunListQueryParameters | Parameter kueri opsional untuk menyaring daftar run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi daftar run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |

### Lihat Juga

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


