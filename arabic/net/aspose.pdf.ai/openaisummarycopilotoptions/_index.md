---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.OpenAISummaryCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot
type: docs
weight: 930
url: /ar/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## فئة OpenAISummaryCopilotOptions

تمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | يحصل أو يحدد اسم المساعد. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يحدد مجموعة الوثائق التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الإكمال التي يمكن استخدامها خلال فترة التشغيل. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز المطالبة التي يمكن استخدامها خلال فترة التشغيل. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يحدد النموذج المستخدم للمساعد. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | يحصل أو يحدد المطالبة لتوجيه النموذج لتقديم ملخص الوثيقة. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يحدد مسار الملف لملف النص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يحدد قيمة top-p لعينات النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | ينشئ مثيلًا من `OpenAISummaryCopilotOptions` ويقوم بتكوينه باستخدام المندوب المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | يحصل على `OpenAISummaryCopilotOptions` الحالية. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | يحدد اسم المساعد لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف وثيقة PDF إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار وثيقة إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف وثيقة نصية إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يحدد مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة وثائق PDF إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف عدة مسارات وثائق إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف عدة وثائق نصية إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | يحدد التعليمات لخيارات ملخص المساعد. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | يحدد الحد الأقصى لرموز الإكمال لخيارات ملخص المساعد. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | يحدد الحد الأقصى لرموز المطالبة لخيارات ملخص المساعد. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | يحدد النموذج لخيارات ملخص المساعد. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | يحدد المطالبة الملخصة لخيارات ملخص المساعد. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | يحدد درجة الحرارة لخيارات ملخص المساعد. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | يحدد قيمة top P لخيارات ملخص المساعد. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)