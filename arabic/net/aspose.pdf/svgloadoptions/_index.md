---
title: "فئة SvgLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.SvgLoadOptions. تمثل الخيارات لتحميل/استيراد ملف SVG إلى مستند pdf"
type: docs
weight: 10390
url: /ar/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

يمثل خيارات تحميل/استيراد ملف SVG إلى مستند pdf.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | ضبط حجم صفحة pdf ليتناسب مع حجم svg |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | يحصل أو يعيّن معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل. حاليًا المحرك الجديد في مرحلة الاختبار B، لذا يتم تعيين هذه القيمة افتراضيًا إلى ConversionEngines.LegacyEngine |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


