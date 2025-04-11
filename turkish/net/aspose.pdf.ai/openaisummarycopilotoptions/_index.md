---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAISummaryCopilotOptions sınıfı. OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.
type: docs
weight: 930
url: /tr/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions sınıfı

OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Asistanın adını alır veya ayarlar. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | İşlenecek belgelerin koleksiyonunu alır veya ayarlar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum tamamlama jetonlarının sayısını alır veya ayarlar. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum istem jetonlarının sayısını alır veya ayarlar. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Asistan için kullanılacak modeli alır veya ayarlar. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Modelin bir belge özeti sağlaması için talimat vermek üzere istemi alır veya ayarlar. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Asistan sistem talimatlarını içeren metin dosyasının dosya yolunu alır veya ayarlar. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Model için kullanılacak örnekleme sıcaklığını alır veya ayarlar. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Nucleus örnekleme için üst-p değerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | `OpenAISummaryCopilotOptions`'ın yeni bir örneğini oluşturur. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | `OpenAISummaryCopilotOptions` örneğini oluşturur ve sağlanan delegasyonu kullanarak yapılandırır. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Mevcut `OpenAISummaryCopilotOptions`'ı alır. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Özet copilot seçenekleri için asistan adını ayarlar. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Özet copilot seçenekleri için belge koleksiyonuna bir PDF belgesi ekler. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Özet copilot seçenekleri için belge koleksiyonuna bir belge yolu ekler. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Özet copilot seçenekleri için belge koleksiyonuna bir metin belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Özet copilot seçenekleri için belge koleksiyonunu ayarlar. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla PDF belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla belge yolu ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Özet copilot seçenekleri için belge koleksiyonuna birden fazla metin belgesi ekler. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Özet copilot seçenekleri için talimatları ayarlar. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Özet copilot seçenekleri için maksimum tamamlama jetonlarını ayarlar. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Özet copilot seçenekleri için maksimum istem jetonlarını ayarlar. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Özet copilot seçenekleri için modeli ayarlar. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Özet copilot seçenekleri için özet istemini ayarlar. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Özet copilot seçenekleri için sıcaklığı ayarlar. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Özet copilot seçenekleri için üst P değerini ayarlar. |

### Ayrıca Bakınız

* sınıf [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* arayüz [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)