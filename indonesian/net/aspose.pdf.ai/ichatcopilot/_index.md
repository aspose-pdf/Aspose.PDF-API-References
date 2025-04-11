---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Antarmuka Aspose.Pdf.AI.IChatCopilot. Mewakili copilot obrolan untuk berinteraksi dengan dokumen melalui model AI
type: docs
weight: 470
url: /id/net/aspose.pdf.ai/ichatcopilot/
---
## Antarmuka IChatCopilot

Mewakili copilot obrolan untuk berinteraksi dengan dokumen melalui model AI.

```csharp
public interface IChatCopilot : IAICopilot
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Menghapus konteks secara asinkron. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Mendapatkan respons secara asinkron untuk daftar pesan yang diberikan. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Mendapatkan respons secara asinkron untuk pesan yang diberikan. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Menyimpan konteks secara asinkron ke file JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Menyimpan respons secara asinkron untuk daftar pesan yang diberikan ke file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Menyimpan respons secara asinkron untuk pesan yang diberikan ke file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Menyimpan respons secara asinkron untuk daftar pesan yang diberikan ke file dengan format yang ditentukan. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Menyimpan respons secara asinkron untuk pesan yang diberikan ke file dengan format yang ditentukan. |

### Lihat Juga

* antarmuka [IAICopilot](../iaicopilot/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)