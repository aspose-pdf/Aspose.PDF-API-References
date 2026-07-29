---
title: "الفئة OpenAISummaryCopilotOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAISummaryCopilotOptions. تمثّل الخيارات لتكوين OpenAICopilot."
type: docs
weight: 1010
url: /ar/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions class

يمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | يحصل أو يعيّن اسم المساعد. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يضبط مجموعة المستندات التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال تشغيل العملية. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/maxprompttokens/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد رموز المطالبة التي قد تُستخدم خلال تشغيل العملية. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم للمساعد. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | يحصل أو يعيّن المطالبة لتوجيه النموذج لتوفير ملخص المستند. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يضبط مسار الملف للنص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يضبط قيمة top-p لتقنية العينة النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | ينشئ مثيلًا من `OpenAISummaryCopilotOptions` ويكوّنه باستخدام المفوض المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | يحصل على الـ `OpenAISummaryCopilotOptions` الحالي. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | يعيّن اسم المساعد لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار المستند إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف مستند نصي إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يعيّن مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة مستندات PDF إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف عدة مسارات مستندات إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف عدة مستندات نصية إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | يعيّن التعليمات لخيارات ملخص المساعد. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | يضبط الحد الأقصى لرموز الإكمال لخيارات المساعد الملخص. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | يضبط الحد الأقصى لرموز المطالبة لخيارات المساعد الملخص. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | يضبط النموذج لخيارات المساعد الملخص. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | يضبط مطالبة الملخص لخيارات المساعد الملخص. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | يضبط درجة الحرارة لخيارات المساعد الملخص. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | يضبط قيمة top P لخيارات المساعد الملخص. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


