---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.ChatMessage. رسالة إكمال دردشة تم إنشاؤها بواسطة النموذج
type: docs
weight: 190
url: /ar/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

رسالة إكمال دردشة تم إنشاؤها بواسطة النموذج.

```csharp
public class ChatMessage
```

## Constructors

| Name | Description |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | يقوم بتهيئة مثيل جديد من فئة `ChatMessage`. |

## Properties

| Name | Description |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | يحصل على محتويات الرسالة أو يحددها. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | يحصل على اسم اختياري للمشارك أو يحدده. يوفر معلومات النموذج لتمييز بين المشاركين من نفس الدور. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | يحصل على دور مؤلف الرسالة أو يحدده. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | يحصل على استدعاء الأداة الذي تستجيب له هذه الرسالة أو يحدده. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | يحصل على استدعاءات الأداة التي تم إنشاؤها بواسطة النموذج، مثل استدعاءات الوظائف. |

## Methods

| Name | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | ينشئ كائن ChatMessage جديد يمثل رسالة مساعد. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | ينشئ كائن ChatMessage جديد يمثل رسالة نظام. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | ينشئ كائن ChatMessage جديد يمثل رسالة مستخدم. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)