---
title: "SvgLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل خيارات تحميل/استيراد ملف SVG إلى مستند pdf."
type: docs
weight: 1450
url: /ar/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

يمثل خيارات تحميل/استيراد ملف SVG إلى مستند pdf.

يظهر نوع SvgLoadOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| SvgLoadOptions() | ينشئ مثيلاً جديدًا من فئة SvgLoadOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| warning_handler | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. <br/>            تُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. <br/>            Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم أيضًا Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |
| load_format | يمثل تنسيق الملف الذي تصفه [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_info | يحصل أو يضبط معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند.<br/>            NOTE أن هذا المعامل يعمل فقط عندما يكون ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | ضبط حجم صفحة PDF ليتناسب مع حجم SVG |
| conversion_engine | يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل.<br/>            حاليًا المحرك الجديد في مرحلة اختبار B، لذا يتم تعيين هذه القيمة افتراضيًا إلى <br/>            ConversionEngines.LegacyEngine |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

