---
title: "الفئة OpenAIChatCopilotOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIChatCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot"
type: docs
weight: 890
url: /ar/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions class

يمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | يحصل أو يعيّن اسم المساعد. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | يحصل أو يضبط مسار الملف لملف النسخ الاحتياطي للسياق بصيغة JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يضبط مجموعة المستندات التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد رموز الإكمال التي قد تُستخدم خلال تشغيل العملية. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/maxprompttokens/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد رموز المطالبة التي قد تُستخدم خلال تشغيل العملية. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يضبط النموذج المستخدم للمساعد. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم استعادة السياق من النسخة الاحتياطية. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يضبط مسار الملف للنص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يضبط درجة حرارة العينة المستخدمة للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يضبط قيمة top-p لتقنية العينة النواة. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | يحصل أو يضبط استراتيجية القطع للموضوع. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | يحصل أو يضبط عدد الأيام قبل انتهاء صلاحية مخزن المتجهات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | ينشئ مثيلاً جديدًا من `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | ينشئ مثيلاً من `OpenAIChatCopilotOptions` ويكوّنّه باستخدام المفوض المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | يحصل على `OpenAIChatCopilotOptions` الحالي. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | يضبط اسم المساعد لخيارات مساعد الدردشة. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | يضبط مسار الملف لملف النسخ الاحتياطي للسياق بصيغة JSON في خيارات مساعد الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار المستند إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف مستند نصي إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يضبط مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف عدة مستندات PDF إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف عدة مسارات مستندات إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف عدة مستندات نصية إلى مجموعة Document لخيارات مساعد الدردشة. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | يضبط التعليمات لخيارات مساعد الدردشة. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | يضبط الحد الأقصى لرموز الإكمال لخيارات مساعد الدردشة. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | يضبط الحد الأقصى لرموز المطالبة لخيارات مساعد الدردشة. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | يضبط النموذج لخيارات مساعد الدردشة. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | يضبط ما إذا كان سيتم استعادة السياق من النسخة الاحتياطية في خيارات مساعد الدردشة. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | يضبط درجة الحرارة لخيارات مساعد الدردشة. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | يضبط قيمة top P لخيارات مساعد الدردشة. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | يضبط استراتيجية القطع لخيارات مساعد الدردشة. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | يضبط عدد الأيام لانتهاء صلاحية مخزن المتجهات في خيارات مساعد الدردشة. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


