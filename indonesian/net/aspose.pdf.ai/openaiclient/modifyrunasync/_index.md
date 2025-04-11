---
title: OpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Memodifikasi run yang ada dalam sebuah thread secara asinkron
type: docs
weight: 400
url: /id/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## Metode OpenAIClient.ModifyRunAsync

Memodifikasi run yang ada dalam sebuah thread secara asinkron.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID dari run yang akan dimodifikasi. |
| assistantModifyRequest | RunModifyRequest | Detail permintaan untuk memodifikasi run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari modifikasi run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika thread Id adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika run Id adalah null atau kosong. |

### Lihat Juga

* kelas [RunResponse](../../runresponse/)
* kelas [RunModifyRequest](../../runmodifyrequest/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)