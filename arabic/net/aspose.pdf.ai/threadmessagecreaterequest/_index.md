---
title: "الفئة ThreadMessageCreateRequest"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.ThreadMessageCreateRequest. تمثل طلبًا لإنشاء رسالة داخل سلسلة."
type: docs
weight: 1210
url: /ar/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

يمثل طلبًا لإنشاء رسالة داخل سلسلة.

```csharp
public class ThreadMessageCreateRequest
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | يحصل أو يضبط قائمة بالملفات المرفقة بالرسالة. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | يحصل أو يضبط محتوى الرسالة. يمكن أن يكون سلسلة نصية أو مصفوفة من أجزاء المحتوى. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | يحصل أو يضبط دور الكيان الذي ينشئ الرسالة. القيم المسموح بها تشمل: \"user\", \"assistant\". |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | ينشئ `ThreadMessageCreateRequest` جديدًا مع تعيين الدور إلى Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | ينشئ `ThreadMessageCreateRequest` جديدًا مع تعيين الدور إلى User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | يضبط المرفقات لطلب رسالة السلسلة. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | يضيف محتوى رسالة إلى طلب رسالة السلسلة. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | يضبط محتويات الرسالة لطلب رسالة السلسلة. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | يضبط البيانات الوصفية لطلب رسالة السلسلة. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


