---
title: "Delegate HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "يمكنك تعيين لهذا الخاصية delegate تم إنشاؤه من طريقة مخصصة تنفّذ إنشاء عنوان URL لملف CSS المشار إليه في مستند HTML المُولَّد. على سبيل المثال، إذا كنت تريد جعل CSS مشارًا إليه في HTML على سبيل المثال كـ otherPage.ASPXCssIDzjjkklj، فيجب أن تُعيد هذه الاستراتيجية المخصصة otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /ar/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

يمكنك تعيين لهذا الخاصية delegate تم إنشاؤه من طريقة مخصصة تنفّذ إنشاء عنوان URL لملف CSS المشار إليه في مستند HTML المُولَّد. على سبيل المثال، إذا كنت تريد جعل CSS مشارًا إليه في HTML على سبيل المثال كـ "otherPage.ASPX?CssID=zjjkklj"، فيجب أن تُعيد هذه الاستراتيجية المخصصة "otherPage.ASPX?CssID=zjjkklj".

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | يمثّل مجموعة من البيانات التي يمكن استخدامها لإنشاء عنوان URL لملف CSS. |

### قيمة الإرجاع

يجب أن تُعيد سلسلة تمثّل عنوان URL لملف CSS أو قالب URL.

### انظر أيضًا

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


