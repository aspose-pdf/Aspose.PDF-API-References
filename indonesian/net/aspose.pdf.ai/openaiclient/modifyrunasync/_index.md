---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Memodifikasi run yang ada dalam thread secara asynchronous."
type: docs
weight: 410
url: /id/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync method

Memodifikasi run yang ada dalam thread secara asynchronous.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadId | String | ID dari thread yang berisi run. |
| runId | String | ID run yang akan dimodifikasi. |
| assistantModifyRequest | RunModifyRequest | Detail permintaan untuk memodifikasi run. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Task yang mewakili operasi asynchronous. Hasil task berisi respons dari modifikasi run.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID thread bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika ID run null atau kosong. |

### Lihat Juga

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


