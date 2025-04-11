---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.SvgLoadOptions. تمثل الخيارات لتحميل/استيراد ملف SVG إلى مستند PDF
type: docs
weight: 10210
url: /ar/net/aspose.pdf/svgloadoptions/
---
## فئة SvgLoadOptions

تمثل الخيارات لتحميل/استيراد ملف SVG إلى مستند PDF.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | ضبط حجم صفحة PDF على حجم SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | يحصل أو يحدد معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | يسمح باختيار محرك التحويل الذي سيكون قيد الاستخدام أثناء التحويل. حاليًا، المحرك الجديد في مرحلة اختبار B، لذا يتم تعيين هذه القيمة بشكل افتراضي إلى ConversionEngines.LegacyEngine |

### انظر أيضًا

* فئة [LoadOptions](../loadoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)