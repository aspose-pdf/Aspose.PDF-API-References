---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.VectorStoreFileResponse. استجابة ملف مخزن المتجهات
type: docs
weight: 1350
url: /ar/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

استجابة ملف مخزن المتجهات.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | يحصل أو يحدد الطابع الزمني لنظام Unix (بالثواني) عند إنشاء ملف مخزن المتجهات. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | يحصل أو يحدد تفاصيل الاستجابة. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | يحصل أو يحدد خطأ استجابة HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | يحصل أو يحدد معلومات الخطأ. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | يحصل أو يحدد رؤوس استجابة HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | يحصل أو يحدد رمز حالة HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | يحصل أو يحدد المعرف، الذي يمكن الإشارة إليه في نقاط نهاية API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | يشير إلى ما إذا كانت الاستجابة ناجحة. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | يحصل أو يحدد آخر خطأ مرتبط بهذا الملف المخزن للمتجهات. سيكون فارغًا إذا لم يكن هناك أخطاء. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | يحصل أو يحدد نوع الكائن، الذي يكون دائمًا vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | يحصل على عبارة سبب الخطأ. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | يحصل أو يحدد حالة ملف مخزن المتجهات، والتي يمكن أن تكون إما قيد المعالجة، مكتملة، ملغاة، أو فاشلة. تشير الحالة المكتملة إلى أن ملف مخزن المتجهات جاهز للاستخدام. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | يحصل أو يحدد إجمالي استخدام مخزن المتجهات بالبايت. لاحظ أن هذا قد يختلف عن حجم الملف الأصلي. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | يحصل أو يحدد معرف مخزن المتجهات الذي يرتبط به الملف. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)