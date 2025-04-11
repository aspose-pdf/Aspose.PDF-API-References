---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse class. يمثل خيطًا يحتوي على رسائل
type: docs
weight: 1180
url: /ar/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

يمثل خيطًا يحتوي على رسائل.

```csharp
public class ThreadResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadResponse](threadresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | يحصل على أو يحدد الطابع الزمني لنظام Unix (بالثواني) عندما تم إنشاء الخيط. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل على أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل على أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل على أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل على أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل على أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | يحصل على أو يحدد المعرف، الذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | يحصل على أو يحدد مجموعة من 16 زوجًا من المفاتيح والقيم التي يمكن إرفاقها بكائن. يمكن أن يكون هذا مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بطول أقصى 64 حرفًا والقيم بطول أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | يحصل على أو يحدد نوع الكائن، الذي يكون دائمًا خيطًا. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | يحصل على أو يحدد مجموعة من الموارد المتاحة لأدوات المساعد في هذا الخيط. الموارد محددة بنوع الأداة. على سبيل المثال، تتطلب أداة code_interpreter قائمة بمعرفات الملفات، بينما تتطلب أداة file_search قائمة بمعرفات مخزن المتجهات. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)