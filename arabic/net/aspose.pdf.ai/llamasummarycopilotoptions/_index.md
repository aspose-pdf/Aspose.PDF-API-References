---
title: "الفئة LlamaSummaryCopilotOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.LlamaSummaryCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot"
type: docs
weight: 800
url: /ar/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

يمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يضبط مجموعة المستندات التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال تشغيل العملية. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم للمساعد. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | يحصل أو يعيّن المطالبة لتوجيه النموذج لتوفير ملخص المستند. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يضبط مسار الملف للنص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | يحصل أو يضبط قيمة top-p لتقنية العينة النواة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | ينشئ مثيلاً جديداً من `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | ينشئ مثيلاً من `LlamaSummaryCopilotOptions` ويقوم بتهيئته باستخدام المفوض المقدم. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | يحصل على `LlamaSummaryCopilotOptions` الحالي. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار المستند إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف مستند نصي إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يعيّن مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة مستندات PDF إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف عدة مسارات مستندات إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف عدة مستندات نصية إلى مجموعة المستندات لخيارات ملخص المساعد. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | يعيّن التعليمات لخيارات ملخص المساعد. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | يضبط الحد الأقصى لرموز الإكمال لخيارات المساعد الملخص. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | يضبط النموذج لخيارات المساعد الملخص. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | يضبط مطالبة الملخص لخيارات المساعد الملخص. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | يضبط درجة الحرارة لخيارات المساعد الملخص. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | يضبط قيمة top P لخيارات المساعد الملخص. |

### انظر أيضًا

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


