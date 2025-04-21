---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.LlamaSummaryCopilot. Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan untuk membuat klien Llama, mengonfigurasi opsi, dan menggunakan copilot ringkasan. Catatan Copilot ini menggunakan API penyelesaian, sehingga jumlah total teks yang dapat dikirim dibatasi oleh jendela konteks model.
type: docs
weight: 740
url: /id/net/aspose.pdf.ai/llamasummarycopilot/
---
## Kelas LlamaSummaryCopilot

Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan untuk membuat klien Llama, mengonfigurasi opsi, dan menggunakan copilot ringkasan. Catatan: Copilot ini menggunakan API penyelesaian, sehingga jumlah total teks yang dapat dikirim dibatasi oleh jendela konteks model.

```csharp
// Create AI client.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Create copilot options.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...create using delegate.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Create summary copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// Get summary text.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Get summary document.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Get summary document with page info.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Save summary as PDF document.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Save summary with specified format.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Menginisialisasi instance baru dari kelas `LlamaSummaryCopilot`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Lihat Juga

* antarmuka [ISummaryCopilot](../isummarycopilot/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)