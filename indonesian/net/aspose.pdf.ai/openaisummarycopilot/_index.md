---
title: "Kelas OpenAISummaryCopilot"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OpenAISummaryCopilot. Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan untuk membuat klien OpenAI dengan mengkonfigurasi opsi dan menggunakan summary copilot."
type: docs
weight: 1000
url: /id/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan membuat klien OpenAI, mengonfigurasi opsi, dan menggunakan summary copilot.

```csharp
// Buat klien AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Buat opsi copilot.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...buat menggunakan delegate.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Buat copilot ringkasan.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// Dapatkan teks ringkasan.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Dapatkan dokumen ringkasan.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Dapatkan dokumen ringkasan dengan info halaman.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Simpan ringkasan sebagai dokumen PDF.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Simpan ringkasan dengan format yang ditentukan.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Menginisialisasi instance baru dari kelas `OpenAISummaryCopilot`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Lihat Juga

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


