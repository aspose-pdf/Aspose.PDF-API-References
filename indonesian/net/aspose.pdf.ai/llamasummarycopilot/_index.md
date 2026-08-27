---
title: "Kelas LlamaSummaryCopilot"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.LlamaSummaryCopilot. Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan untuk membuat klien Llama, mengonfigurasi opsi, dan menggunakan copilot ringkasan. Catatan: Copilot ini menggunakan API penyelesaian sehingga jumlah total teks yang dapat dikirim dibatasi oleh jendela konteks model."
type: docs
weight: 790
url: /id/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

Menyediakan fungsionalitas untuk mendapatkan ringkasan dokumen menggunakan model AI. Contoh penggunaan membuat klien Llama, mengonfigurasi opsi, dan menggunakan copilot ringkasan. Catatan: Copilot ini menggunakan API penyelesaian, sehingga total teks yang dapat dikirim dibatasi oleh jendela konteks model.

```csharp
// Buat klien AI.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Buat opsi copilot.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...membuat menggunakan delegasi.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Buat copilot ringkasan.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

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
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Menginisialisasi sebuah instance baru dari kelas `LlamaSummaryCopilot`. |

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

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


