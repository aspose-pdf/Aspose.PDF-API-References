---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. هذا التعداد يسرد الاستراتيجيات الممكنة للتعامل مع مثل هذه الأخطاء."
type: docs
weight: 5790
url: /ar/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. هذا التعداد يسرد الاستراتيجيات الممكنة للتعامل مع مثل هذه الأخطاء.

## الحقول

| حقل | الوصف |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | هذه هي الطريقة الأكثر مرونة - يجب على الكود المخصص توفير (في خاصية WarningCallback) معالج خاص سيتم استدعاؤه عند اكتشاف خطأ تنسيق. يمكن لهذا المعالج، على سبيل المثال، تسجيل أو عد الأخطاء إلخ وسيقدم قرارًا ما إذا كان يمكن متابعة المعالجة لهذا الخطأ أو ذاك. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | في هذه الحالة سيتوقف التحويل فورًا وسيتم رمي الاستثناء فورًا بعد اكتشاف أول خطأ تنسيق |
| [TryIgnore](#TryIgnore) | في هذه الحالة سيُطلب من المحول محاولة المتابعة مع التحويل وتجاهل أخطاء التنسيق المكتشفة. في هذه الحالة لا يُضمن النجاح، قد تحدث مشاكل خطيرة لاحقًا في المحول، وفي مثل هذه الحالة سيتم رمي استثناء مع قائمة بأخطاء التنسيق المكتشفة. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

هذه هي الطريقة الأكثر مرونة - يجب على الكود المخصص توفير (في خاصية WarningCallback) معالج خاص سيتم استدعاؤه عند اكتشاف خطأ تنسيق. يمكن لهذا المعالج، على سبيل المثال، تسجيل أو عد الأخطاء إلخ وسيقدم قرارًا ما إذا كان يمكن متابعة المعالجة لهذا الخطأ أو ذاك.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

في هذه الحالة سيتوقف التحويل فورًا وسيتم رمي الاستثناء فورًا بعد اكتشاف أول خطأ تنسيق

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

في هذه الحالة سيُطلب من المحول محاولة المتابعة مع التحويل وتجاهل أخطاء التنسيق المكتشفة. في هذه الحالة لا يُضمن النجاح، قد تحدث مشاكل خطيرة لاحقًا في المحول، وفي مثل هذه الحالة سيتم رمي استثناء مع قائمة بأخطاء التنسيق المكتشفة.
