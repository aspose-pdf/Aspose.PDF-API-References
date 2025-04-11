---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.ThreadMessageCreateRequest. تمثل طلبًا لإنشاء رسالة ضمن سلسلة
type: docs
weight: 1120
url: /ar/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

تمثل طلبًا لإنشاء رسالة ضمن سلسلة.

```csharp
public class ThreadMessageCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | يحصل أو يحدد قائمة الملفات المرفقة بالرسالة. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | يحصل أو يحدد محتوى الرسالة. يمكن أن يكون سلسلة أو مصفوفة من أجزاء المحتوى. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | يحصل أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | يحصل أو يحدد دور الكيان الذي ينشئ الرسالة. القيم المسموح بها تشمل: "مستخدم"، "مساعد". |

## Methods

| Name | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | ينشئ طلب `ThreadMessageCreateRequest` جديد مع تعيين الدور إلى مساعد. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | ينشئ طلب `ThreadMessageCreateRequest` جديد مع تعيين الدور إلى مستخدم. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | يحدد المرفقات لطلب رسالة السلسلة. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | يضيف محتوى رسالة إلى طلب رسالة السلسلة. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | يحدد محتويات الرسالة لطلب رسالة السلسلة. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | يحدد البيانات الوصفية لطلب رسالة السلسلة. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)