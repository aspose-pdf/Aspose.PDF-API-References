---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes enum. يمكن أن يحتوي مستند XSLFO المصدر على أخطاء في التنسيق. يقوم هذا التعداد بإدراج استراتيجيات ممكنة للتعامل مع مثل هذه الأخطاء في التنسيق
type: docs
weight: 11540
url: /ar/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

يمكن أن يحتوي مستند XSLFO المصدر على أخطاء في التنسيق. يقوم هذا التعداد بإدراج استراتيجيات ممكنة للتعامل مع مثل هذه الأخطاء في التنسيق

```csharp
public enum ParsingErrorsHandlingTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TryIgnore | `0` | في هذه الحالة، سيتم توجيه المحول لمحاولة المتابعة مع التحويل وتجاهل الأخطاء في التنسيق التي تم العثور عليها. في هذه الحالة، النجاح غير مضمون، ويمكن أن تحدث مشاكل خطيرة لاحقًا في المحول، وفي هذه الحالة سيتم طرح استثناء مع قائمة بالأخطاء في التنسيق التي تم العثور عليها. |
| ThrowExceptionImmediately | `1` | في هذه الحالة، سيتم إيقاف التحويل على الفور وسيتم طرح استثناء على الفور بعد اكتشاف أول خطأ في التنسيق |
| InvokeCustomHandler | `2` | هذه هي الطريقة الأكثر مرونة - يجب أن يوفر الكود المخصص (في خاصية WarningCallback) معالجًا خاصًا سيتم استدعاؤه عند اكتشاف خطأ في التنسيق. يمكن أن يقوم هذا المعالج، على سبيل المثال، بتسجيل الأخطاء أو عدها وما إلى ذلك، وسيوفر قرارًا بشأن ما إذا كان يمكن متابعة المعالجة لهذا الخطأ أو ذاك. |

### See Also

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)