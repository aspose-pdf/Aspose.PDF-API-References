---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.LlamaSummaryCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot
type: docs
weight: 750
url: /ar/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## فئة LlamaSummaryCopilotOptions

تمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يحدد مجموعة الوثائق التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الإكمال التي يمكن استخدامها خلال فترة التشغيل. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | يحصل أو يحدد النموذج المستخدم للمساعد. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | يحصل أو يحدد الموجه لإرشاد النموذج لتقديم ملخص الوثيقة. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يحدد مسار الملف لملف النص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | يحصل أو يحدد قيمة top-p لعينات النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | ينشئ مثيلًا من `LlamaSummaryCopilotOptions` ويقوم بتكوينه باستخدام المندوب المقدم. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | يحصل على `LlamaSummaryCopilotOptions` الحالية. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف وثيقة PDF إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار وثيقة إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف وثيقة نصية إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يحدد مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة وثائق PDF إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف عدة مسارات وثائق إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف عدة وثائق نصية إلى مجموعة الوثائق لخيارات ملخص المساعد. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | يحدد التعليمات لخيارات ملخص المساعد. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | يحدد الحد الأقصى لرموز الإكمال لخيارات ملخص المساعد. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | يحدد النموذج لخيارات ملخص المساعد. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | يحدد الموجه الملخص لخيارات ملخص المساعد. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | يحدد درجة الحرارة لخيارات ملخص المساعد. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | يحدد قيمة top P لخيارات ملخص المساعد. |

### انظر أيضًا

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)