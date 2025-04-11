---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: يمكنك تعيين هذه الخاصية إلى مفوض تم إنشاؤه من طريقة مخصصة تقوم بتنفيذ إنشاء عنوان URL لـ CSS المشار إليه في وثيقة HTML الناتجة. على سبيل المثال، إذا كنت تريد جعل CSS المشار إليه في HTML مثل "otherPage.ASPXCssIDzjjkklj" فإن هذه الاستراتيجية المخصصة يجب أن تعيد "otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5600
url: /ar/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## مفوض HtmlSaveOptions.CssUrlMakingStrategy

يمكنك تعيين هذه الخاصية إلى مفوض تم إنشاؤه من طريقة مخصصة تقوم بتنفيذ إنشاء عنوان URL لـ CSS المشار إليه في وثيقة HTML الناتجة. على سبيل المثال، إذا كنت تريد جعل CSS المشار إليه في HTML مثل "otherPage.ASPX?CssID=zjjkklj" فإن هذه الاستراتيجية المخصصة يجب أن تعيد "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | يمثل مجموعة من البيانات التي يمكن استخدامها لإنشاء عنوان URL لـ CSS |

### قيمة الإرجاع

يجب أن تعيد سلسلة تمثل عنوان URL لـ CSS أو قالب عنوان URL

### انظر أيضًا

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)