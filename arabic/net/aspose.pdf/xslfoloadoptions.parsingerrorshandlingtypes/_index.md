---
title: "التعداد XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا التعداد الاستراتيجيات الممكنة للتعامل مع مثل هذه الأخطاء التنسيقية"
type: docs
weight: 11730
url: /ar/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا التعداد الاستراتيجيات الممكنة للتعامل مع مثل هذه الأخطاء التنسيقية.

```csharp
public enum ParsingErrorsHandlingTypes
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| TryIgnore | `0` | في هذه الحالة سيُطلب من المحول محاولة المتابعة مع التحويل وتجاهل أخطاء التنسيق المكتشفة. في هذه الحالة لا يُضمن النجاح، وقد تحدث مشاكل خطيرة لاحقًا في المحول، وفي مثل هذه الحالة سيتم رمي استثناء يحتوي على قائمة بأخطاء التنسيق المكتشفة. |
| ThrowExceptionImmediately | `1` | في هذه الحالة سيتوقف التحويل فورًا وسيُرمى استثناء فور اكتشاف أول خطأ تنسيق. |
| InvokeCustomHandler | `2` | هذه هي الطريقة الأكثر مرونة - يجب على الشيفرة المخصصة توفير (في خاصية WarningCallback) معالج خاص سيتم استدعاؤه عند اكتشاف خطأ في التنسيق. يمكن لهذا المعالج، على سبيل المثال، تسجيل الأخطاء أو عدّها وما إلى ذلك، وسيحدد ما إذا كان يمكن متابعة المعالجة لهذا الخطأ أو ذاك. |

### انظر أيضًا

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


