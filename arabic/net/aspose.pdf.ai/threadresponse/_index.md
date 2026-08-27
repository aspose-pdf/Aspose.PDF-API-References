---
title: "الفئة ThreadResponse"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.ThreadResponse. تمثّل سلسلة تحتوي على رسائل"
type: docs
weight: 1270
url: /ar/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

يمثل سلسلة تحتوي على رسائل.

```csharp
public class ThreadResponse : BaseResponse
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ThreadResponse](threadresponse/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | يحصل أو يعيّن طابع الوقت Unix (بالثواني) للوقت الذي تم إنشاء السلسلة فيه. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يتم الحصول على أو تعيين تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يتم الحصول على أو تعيين خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يتم الحصول على أو تعيين معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يتم الحصول على أو تعيين رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يتم الحصول على أو تعيين رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | يحصل أو يعيّن المعرف، الذي يمكن الإشارة إليه في نقاط النهاية API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | يتم الحصول على أو تعيين مجموعة من 16 زوجًا من المفتاح والقيمة يمكن إرفاقها بكائن. يمكن أن يكون ذلك مفيدًا لتخزين معلومات إضافية حول الكائن بتنسيق منظم. يمكن أن تكون المفاتيح بحد أقصى 64 حرفًا والقيم بحد أقصى 512 حرفًا. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | يحصل أو يعيّن نوع الكائن، والذي يكون دائمًا thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يتم الحصول على عبارة سبب الخطأ. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | يحصل أو يعيّن مجموعة من الموارد التي تُتاح لأدوات المساعد في هذه السلسلة. الموارد تكون محددة حسب نوع الأداة. على سبيل المثال، أداة code_interpreter تتطلب قائمة بمعرفات الملفات (file IDs)، بينما أداة file_search تتطلب قائمة بمعرفات مخازن المتجهات (vector store IDs). |

### انظر أيضًا

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


