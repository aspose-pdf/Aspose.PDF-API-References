---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot
type: docs
weight: 900
url: /ar/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## فئة OpenAIImageDescriptionCopilotOptions

تمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | يحصل أو يحدد اسم المساعد. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يحدد مجموعة الوثائق التي سيتم معالجتها. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | يحصل أو يحدد الموجه لإرشاد النموذج لتقديم وصف الصورة. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | يحصل أو يحدد مستوى التفاصيل للصورة إذا تم تحديده من قبل المستخدم. "منخفض" يستخدم عدد أقل من الرموز، يمكنك اختيار دقة عالية باستخدام "مرتفع". إذا لم يتم تعيينه، الافتراضي هو "تلقائي". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الإكمال التي يمكن استخدامها خلال فترة التشغيل. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الموجه التي يمكن استخدامها خلال فترة التشغيل. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | يحصل أو يحدد نموذج الرؤية الذي سيتم استخدامه للمساعد. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يحدد مسار الملف لملف النص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة التي سيتم استخدامها للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يحدد قيمة top-p لعينات النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | ينشئ مثيلًا من `OpenAIImageDescriptionCopilotOptions` ويقوم بتكوينه باستخدام المندوب المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | يحصل على `OpenAIImageDescriptionCopilotOptions` الحالية. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | يحدد اسم المساعد لخيارات مساعد وصف الصورة. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف وثيقة PDF إلى مجموعة الوثائق لخيارات مساعد وصف الصورة. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | يضيف مسار وثيقة إلى مجموعة الوثائق لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يحدد مجموعة الوثائق لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة وثائق PDF إلى مجموعة الوثائق لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | يضيف عدة مسارات وثائق إلى مجموعة الوثائق لخيارات مساعد وصف الصورة. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | يحدد الموجه لخيارات مساعد وصف الصورة. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | يحدد مستوى تفاصيل الصورة. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | يحدد التعليمات لخيارات مساعد وصف الصورة. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | يحدد الحد الأقصى لرموز الإكمال لخيارات مساعد وصف الصورة. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | يحدد الحد الأقصى لرموز الموجه لخيارات مساعد وصف الصورة. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | يحدد النموذج لخيارات مساعد وصف الصورة. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | يحدد درجة الحرارة لخيارات مساعد وصف الصورة. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | يحدد قيمة top P لخيارات مساعد وصف الصورة. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)