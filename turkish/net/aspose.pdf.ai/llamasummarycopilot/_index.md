---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilot sınıfı. AI modellerini kullanarak belge özetleri alma işlevselliği sağlar. Llama istemcisi oluşturma, seçenekleri yapılandırma ve özet yardımcı pilotunu kullanma örnek kullanımı. Not Bu yardımcı pilot, tamamlama API'sini kullanır, bu nedenle gönderilebilecek toplam metin miktarı model bağlam penceresi ile sınırlıdır.
type: docs
weight: 740
url: /tr/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot sınıfı

AI modellerini kullanarak belge özetleri alma işlevselliği sağlar. Llama istemcisi oluşturma, seçenekleri yapılandırma ve özet yardımcı pilotunu kullanma örnek kullanımı. Not: Bu yardımcı pilot, tamamlama API'sini kullanır, bu nedenle gönderilebilecek toplam metin miktarı model bağlam penceresi ile sınırlıdır.

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

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | `LlamaSummaryCopilot` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Ayrıca Bakınız

* arayüz [ISummaryCopilot](../isummarycopilot/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)