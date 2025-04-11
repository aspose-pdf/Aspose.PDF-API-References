---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilotOptions sınıfı. OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.
type: docs
weight: 750
url: /tr/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions sınıfı

OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | İşlenecek belgelerin koleksiyonunu alır veya ayarlar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum tamamlama token sayısını alır veya ayarlar. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Asistan için kullanılacak modeli alır veya ayarlar. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Modelin bir belge özeti sağlaması için talimat vermek üzere istemi alır veya ayarlar. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Asistan sistem talimatlarını içeren metin dosyasının dosya yolunu alır veya ayarlar. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Model için kullanılacak örnekleme sıcaklığını alır veya ayarlar. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Çekirdek örnekleme için top-p değerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | `LlamaSummaryCopilotOptions`'ın yeni bir örneğini oluşturur. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | `LlamaSummaryCopilotOptions` örneğini oluşturur ve sağlanan delegasyonu kullanarak yapılandırır. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Mevcut `LlamaSummaryCopilotOptions`'ı alır. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Özet copilot seçenekleri için belge koleksiyonuna bir PDF belgesi ekler. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Özet copilot seçenekleri için belge koleksiyonuna bir belge yolu ekler. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Özet copilot seçenekleri için belge koleksiyonuna bir metin belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Özet copilot seçenekleri için belge koleksiyonunu ayarlar. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla PDF belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla belge yolu ekler. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla metin belgesi ekler. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Özet copilot seçenekleri için talimatları ayarlar. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Özet copilot seçenekleri için maksimum tamamlama token'larını ayarlar. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Özet copilot seçenekleri için modeli ayarlar. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Özet copilot seçenekleri için özeti istemini ayarlar. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Özet copilot seçenekleri için sıcaklığı ayarlar. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Özet copilot seçenekleri için top P değerini ayarlar. |

### Ayrıca Bakınız

* sınıf [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* arayüz [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)