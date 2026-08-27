---
title: "الفئة OpenAIOcrCopilotOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIOcrCopilotOptions. تمثل الخيارات لتكوين OpenAIOcrCopilot"
type: docs
weight: 990
url: /ar/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

يمثل الخيارات لتكوين OpenAIOcrCopilot.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | يحصل أو يعيّن مستوى التفاصيل لتحليل الصورة. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يضبط مجموعة المستندات التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال تشغيل العملية. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم للمساعد. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | يحصل أو يعيّن الدقة المستخدمة لتحويل صفحات PDF إلى صور. القيمة الافتراضية هي 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يضبط مسار الملف للنص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يضبط قيمة top-p لتقنية العينة النواة. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | يحصل أو يعيّن موجه المستخدم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | ينشئ مثيلاً جديداً من `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | ينشئ مثيلاً من `OpenAIOcrCopilotOptions` ويكوّنه باستخدام المفوض المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | يحصل على `OpenAIOcrCopilotOptions` الحالي. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | يعيّن مستوى التفاصيل لتحليل الصورة. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة المستندات. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | يضيف مسار المستند إلى مجموعة المستندات. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يعيّن مجموعة المستندات. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة مستندات PDF إلى مجموعة المستندات. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | يضيف عدة مسارات مستندات إلى مجموعة المستندات. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | يعيّن الحد الأقصى لرموز الإكمال. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | يعيّن النموذج. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | يعيّن الدقة المستخدمة لتحويل صفحات PDF إلى صور. القيمة الافتراضية هي 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | يعيّن التعليمات لخيارات ocr copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | يعيّن درجة الحرارة. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | يعيّن قيمة top P. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | يعيّن موجه المستخدم. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


