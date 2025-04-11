---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.OpenAIChatCopilotOptions. تمثل الخيارات لتكوين OpenAICopilot
type: docs
weight: 830
url: /ar/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## فئة OpenAIChatCopilotOptions

تمثل الخيارات لتكوين OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | يحصل أو يحدد اسم المساعد. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | يحصل أو يحدد مسار الملف لنسخة احتياطية من JSON للسياق. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | يحصل أو يحدد مجموعة الوثائق التي سيتم معالجتها. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز الإكمال التي يمكن استخدامها خلال فترة التشغيل. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | يحصل أو يحدد الحد الأقصى لعدد رموز المطالبة التي يمكن استخدامها خلال فترة التشغيل. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | يحصل أو يحدد النموذج الذي سيتم استخدامه للمساعد. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان يجب استعادة السياق من النسخة الاحتياطية. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | يحصل أو يحدد مسار الملف لملف النص الذي يحتوي على تعليمات نظام المساعد. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | يحصل أو يحدد درجة حرارة العينة التي سيتم استخدامها للنموذج. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | يحصل أو يحدد قيمة top-p لعينات النواة. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | يحصل أو يحدد استراتيجية الاقتطاع للخيط. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | يحصل أو يحدد عدد الأيام قبل انتهاء صلاحية متجر المتجهات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | ينشئ مثيلًا جديدًا من `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | ينشئ مثيلًا من `OpenAIChatCopilotOptions` ويقوم بتكوينه باستخدام المندوب المقدم. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | يحصل على `OpenAIChatCopilotOptions` الحالية. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | يحدد اسم المساعد لخيارات الدردشة. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | يحدد مسار الملف لنسخة احتياطية من JSON في خيارات الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | يضيف مستند PDF إلى مجموعة المستندات لخيارات الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | يضيف مسار مستند إلى مجموعة المستندات لخيارات الدردشة. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | يضيف مستند نصي إلى مجموعة المستندات لخيارات الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | يحدد مجموعة المستندات لخيارات الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | يضيف مستندات PDF متعددة إلى مجموعة المستندات لخيارات الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | يضيف مسارات مستندات متعددة إلى مجموعة المستندات لخيارات الدردشة. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | يضيف مستندات نصية متعددة إلى مجموعة المستندات لخيارات الدردشة. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | يحدد التعليمات لخيارات الدردشة. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | يحدد الحد الأقصى لرموز الإكمال لخيارات الدردشة. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | يحدد الحد الأقصى لرموز المطالبة لخيارات الدردشة. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | يحدد النموذج لخيارات الدردشة. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | يحدد ما إذا كان يجب استعادة السياق من النسخة الاحتياطية في خيارات الدردشة. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | يحدد درجة الحرارة لخيارات الدردشة. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | يحدد قيمة top P لخيارات الدردشة. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | يحدد استراتيجية الاقتطاع لخيارات الدردشة. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | يحدد عدد الأيام لانتهاء صلاحية متجر المتجهات في خيارات الدردشة. |

### انظر أيضًا

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)