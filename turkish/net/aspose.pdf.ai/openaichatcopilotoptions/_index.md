---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIChatCopilotOptions sınıfı. OpenAICopilot'u yapılandırmak için seçenekleri temsil eder.
type: docs
weight: 830
url: /tr/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions sınıfı

OpenAICopilot'u yapılandırmak için seçenekleri temsil eder.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Asistanın adını alır veya ayarlar. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Bağlam yedek JSON'u için dosya yolunu alır veya ayarlar. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | İşlenecek belgelerin koleksiyonunu alır veya ayarlar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum tamamlama token sayısını alır veya ayarlar. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Çalışma süresince kullanılabilecek maksimum istem token sayısını alır veya ayarlar. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Asistan için kullanılacak modeli alır veya ayarlar. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Yedekten bağlamı geri yükleyip yüklemeyeceğini belirten bir değeri alır veya ayarlar. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Asistan sistem talimatlarını içeren metin dosyası için dosya yolunu alır veya ayarlar. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Model için kullanılacak örnekleme sıcaklığını alır veya ayarlar. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Çekirdek örnekleme için üst-p değerini alır veya ayarlar. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | İpliğin kesme stratejisini alır veya ayarlar. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Vektör deposunun süresi dolmadan önceki gün sayısını alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | `OpenAIChatCopilotOptions`'ın yeni bir örneğini oluşturur. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | `OpenAIChatCopilotOptions` örneğini oluşturur ve sağlanan delegayı kullanarak yapılandırır. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Geçerli `OpenAIChatCopilotOptions`'ı alır. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Sohbet yardımcı pilot seçenekleri için asistan adını ayarlar. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Sohbet yardımcı pilot seçeneklerinde bağlam yedek JSON'u için dosya yolunu ayarlar. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna bir PDF belgesi ekler. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna bir belge yolu ekler. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna bir metin belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonunu ayarlar. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna birden fazla PDF belgesi ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna birden fazla belge yolu ekler. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Sohbet yardımcı pilot seçenekleri için belge koleksiyonuna birden fazla metin belgesi ekler. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Sohbet yardımcı pilot seçenekleri için talimatları ayarlar. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Sohbet yardımcı pilot seçenekleri için maksimum tamamlama token'larını ayarlar. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Sohbet yardımcı pilot seçenekleri için maksimum istem token'larını ayarlar. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Sohbet yardımcı pilot seçenekleri için modeli ayarlar. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Sohbet yardımcı pilot seçenekleri için yedekten bağlamı geri yükleyip yüklemeyeceğini ayarlar. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Sohbet yardımcı pilot seçenekleri için sıcaklığı ayarlar. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Sohbet yardımcı pilot seçenekleri için üst P değerini ayarlar. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Sohbet yardımcı pilot seçenekleri için kesme stratejisini ayarlar. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Sohbet yardımcı pilot seçenekleri için vektör deposu süresi dolma gün sayısını ayarlar. |

### Ayrıca Bakınız

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)