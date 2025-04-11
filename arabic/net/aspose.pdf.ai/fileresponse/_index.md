---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.FileResponse. يمثل كائن FileResponse مستندًا تم تحميله إلى OpenAI
type: docs
weight: 400
url: /ar/net/aspose.pdf.ai/fileresponse/
---
## FileResponse class

يمثل كائن FileResponse مستندًا تم تحميله إلى OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Constructors

| Name | Description |
| --- | --- |
| [FileResponse](fileresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | يحصل أو يحدد حجم الملف، بالبايت. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) لوقت إنشاء الملف. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | يحصل أو يحدد اسم الملف. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | يحصل أو يحدد معرف الملف، الذي يمكن الإشارة إليه في نقاط نهاية API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، الذي يكون دائمًا ملفًا. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | يحصل أو يحدد الغرض المقصود من الملف. القيم المدعومة هي assistants و assistants_output و batch و batch_output و fine-tune و fine-tune-results و vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)