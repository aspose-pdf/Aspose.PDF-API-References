---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions sınıfı. OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.
type: docs
weight: 900
url: /tr/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions sınıfı

OpenAICopilot'ı yapılandırmak için seçenekleri temsil eder.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Asistanın adını alır veya ayarlar. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | İşlenecek belgelerin koleksiyonunu alır veya ayarlar. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Modelin resim açıklaması sağlaması için talimat vermek üzere istemi alır veya ayarlar. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Kullanıcı tarafından belirtilirse resmin detay seviyesini alır veya ayarlar. "low" daha az token kullanır, "high" ile yüksek çözünürlük seçebilirsiniz. Ayarlanmazsa varsayılan "auto" olur. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum tamamlama token sayısını alır veya ayarlar. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum istem token sayısını alır veya ayarlar. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Asistan için kullanılacak görsel modeli alır veya ayarlar. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Asistan sistem talimatlarını içeren metin dosyasının dosya yolunu alır veya ayarlar. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Model için kullanılacak örnekleme sıcaklığını alır veya ayarlar. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Çekirdek örnekleme için top-p değerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | `OpenAIImageDescriptionCopilotOptions`'ın yeni bir örneğini oluşturur. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | `OpenAIImageDescriptionCopilotOptions` örneğini oluşturur ve sağlanan delegasyonu kullanarak yapılandırır. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Mevcut `OpenAIImageDescriptionCopilotOptions`'ı alır. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Resim açıklama copilot seçenekleri için asistan adını ayarlar. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Resim açıklama copilot seçenekleri için belge koleksiyonuna bir PDF belgesi ekler. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Resim açıklama copilot seçenekleri için belge koleksiyonuna bir belge yolu ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Resim açıklama copilot seçenekleri için belge koleksiyonunu ayarlar. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Resim açıklama copilot seçenekleri için belge koleksiyonuna birden fazla PDF belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Resim açıklama copilot seçenekleri için belge koleksiyonuna birden fazla belge yolu ekler. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Resim açıklama copilot seçenekleri için istemi ayarlar. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Resim detay seviyesini ayarlar. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Resim açıklama copilot seçenekleri için talimatları ayarlar. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Resim açıklama copilot seçenekleri için maksimum tamamlama token'larını ayarlar. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Resim açıklama copilot seçenekleri için maksimum istem token'larını ayarlar. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Resim açıklama copilot seçenekleri için modeli ayarlar. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Resim açıklama copilot seçenekleri için sıcaklığı ayarlar. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Resim açıklama copilot seçenekleri için top P değerini ayarlar. |

### Ayrıca Bakınız

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)