---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب اكتشاف مشكلة عائق في طبقة OSHARED في مستند العينة. تمثل وضعية استخدام حجم الصفحة."
type: docs
weight: 2810
url: /ar/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

تنبيه! تم تنفيذ الميزة ولكن لم تُضمّن بعد في واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم اكتشافها في المستند النموذجي. يمثل وضع استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا يسمح بتلائم حجم الصفحة المطلوب. لكن أحيانًا يحدد المحتوى مواضع أفقية أو حجم لا يسمح بوضع المحتوى في حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب في مستند PDF الناتج).

## الحقول

| حقل | الوصف |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | هذا الوضع يحدد هذا السلوك: بعد الحصول على نتيجة التحويل، واكتشاف أن بعض المحتوى قد تم قطعه، يتم توسيع عرض المنظر لتناسب المحتوى وتُعاد عملية التحويل. يسمح هذا الوضع بالحصول على عدد أقل من الصفحات في النتيجة في مثل هذه الحالة ولكنه يتطلب إعادة التصيير (وبالتالي وقت معالجة أكبر). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | في هذا الوضع، ستحصل الصفحات الناتجة على حجم الصفحة المطلوب المحدد في LoadOptions، بغض النظر عما إذا كان المحتوى بعد التحويل يخرج عن حدود الصفحة أم لا. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

هذا الوضع يحدد هذا السلوك: بعد الحصول على نتيجة التحويل، واكتشاف أن بعض المحتوى قد تم قطعه، يتم توسيع عرض المنظر لتناسب المحتوى وتُعاد عملية التحويل. يسمح هذا الوضع بالحصول على عدد أقل من الصفحات في النتيجة في مثل هذه الحالة ولكنه يتطلب إعادة التصيير (وبالتالي وقت معالجة أكبر).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

في هذا الوضع، ستحصل الصفحات الناتجة على حجم الصفحة المطلوب المحدد في LoadOptions، بغض النظر عما إذا كان المحتوى بعد التحويل يخرج عن حدود الصفحة أم لا.
