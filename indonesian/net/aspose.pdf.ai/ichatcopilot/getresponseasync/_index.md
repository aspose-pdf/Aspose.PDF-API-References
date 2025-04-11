---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IChatCopilot. Secara asinkron mendapatkan respons untuk pesan yang diberikan
type: docs
weight: 20
url: /id/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Secara asinkron mendapatkan respons untuk pesan yang diberikan.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | String | Pesan input untuk yang mana respons diminta. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron dengan string respons.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Secara asinkron mendapatkan respons untuk daftar pesan yang diberikan.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| messages | List`1 | Daftar pesan input untuk yang mana respons diminta. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron dengan string respons.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)