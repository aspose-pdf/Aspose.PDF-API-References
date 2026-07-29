---
title: "الفئة OpenAIImageDescriptionCopilotOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. تمثّل الخيارات لتكوين OpenAICopilot"
type: docs
weight: 960
url: /ar/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

يمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | يحصل أو يعيّن اسم المساعد. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يضبط مجموعة المستندات التي سيتم معالجتها. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | يحصل أو يعيّن الموجه لتوجيه النموذج لتقديم وصف الصورة. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | يحصل أو يعيّن مستوى تفاصيل الصورة إذا حدده المستخدم. "low" يستخدم عددًا أقل من الرموز، يمكنك اختيار الدقة العالية باستخدام "high". إذا لم يتم التعيين، يكون الافتراضي "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال تشغيل العملية. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/maxprompttokens/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد رموز المطالبة التي قد تُستخدم خلال تشغيل العملية. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم للمساعد. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يضبط مسار الملف للنص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يضبط قيمة top-p لتقنية العينة النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | ينشئ مثيلًا من `OpenAIImageDescriptionCopilotOptions` ويكوّنه باستخدام المفوض المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | يحصل على `OpenAIImageDescriptionCopilotOptions` الحالي. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | يعيّن اسم المساعد لخيارات مساعد وصف الصورة. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة المستندات لخيارات مساعد وصف الصورة. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | يضيف مسار مستند إلى مجموعة المستندات لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يعيّن مجموعة المستندات لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة مستندات PDF إلى مجموعة المستندات لخيارات مساعد وصف الصورة. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | يضيف عدة مسارات مستندات إلى مجموعة المستندات لخيارات مساعد وصف الصورة. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | يعيّن الموجه لخيارات مساعد وصف الصورة. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | يعيّن مستوى تفاصيل الصورة. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | يعيّن التعليمات لخيارات مساعد وصف الصورة. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | يعيّن الحد الأقصى لرموز الإكمال لخيارات مساعد وصف الصورة. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | يعيّن الحد الأقصى لرموز الموجه لخيارات مساعد وصف الصورة. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | يضبط النموذج لخيارات مساعد وصف الصورة. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | يضبط درجة الحرارة لخيارات مساعد وصف الصورة. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | يضبط قيمة أعلى P لخيارات مساعد وصف الصورة. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


