---
title: "الفئة ChatMessage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.ChatMessage. رسالة إكمال محادثة تم إنشاؤها بواسطة النموذج."
type: docs
weight: 190
url: /ar/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

رسالة إكمال محادثة تم إنشاؤها بواسطة النموذج.

```csharp
public class ChatMessage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | يُهيئ مثيلاً جديداً من الفئة `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | يُهيئ مثيلاً جديداً من الفئة `ChatMessage`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | يحصل أو يعيّن محتوى الرسالة. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | يحصل أو يعيّن اسمًا اختياريًا للمشارك. يوفر معلومات النموذج للتمييز بين المشاركين الذين لهم نفس الدور. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | يحصل أو يعيّن دور مؤلف الرسائل. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | يحصل أو يعيّن استدعاء الأداة الذي ترد عليه هذه الرسالة. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | يحصل أو يعيّن استدعاءات الأدوات التي يولدها النموذج، مثل استدعاءات الدوال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | ينشئ كائناً جديداً من نوع ChatMessage يمثل رسالة المساعد. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | ينشئ كائن ChatMessage جديد يمثل رسالة نظام. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | ينشئ كائن ChatMessage جديد يمثل رسالة مستخدم. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


