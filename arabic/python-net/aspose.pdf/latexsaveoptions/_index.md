---
title: "LaTeXSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "خيارات الحفظ للتصدير إلى تنسيق TeX."
type: docs
weight: 800
url: /ar/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق TeX.

يعرض نوع LaTeXSaveOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| LaTeXSaveOptions() | يُهيئ نسخة جديدة من فئة LaTeXSaveOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| warning_handler | لا شيء |
| save_format | لا شيء |
| close_response | لا شيء |
| extract_ocr_sublayer_only | هذا السمة تُفعِّل الوظيفة لاستخراج الصورة أو النص <br/>            لمستندات PDF التي تحتوي على طبقة فرعية OCR. |
| try_merge_adjacent_same_background_images | أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول)<br/>              مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجوار بعضها.<br/>              في مثل هذه الحالة قد تُنشئ عارضات الصيغ المستهدفة (مثلاً MsWord لصيغة DOCS) حدودًا مرئية بين أجزاء صور الخلفية،<br/>              بسبب اختلاف تقنيات تنعيم حواف الصورة (anti-aliasing) عن Acrobat Reader.<br/>               إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين <br/>              أجزاء صور الخلفية المتماثلة، يرجى محاولة استخدام هذا الإعداد للتخلص <br/>              من هذا التأثير غير المرغوب. <br/>                انتباه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء عملية التحويل بشكل كبير،<br/>              لذا، يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |
| out_directory_path | خاصية لـ |
| pages_count | يرجع عدد الصفحات بعد التحويل. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| add_font_encs(font_encs) | يضيف ترميز خط إلى قائمة ترميزات الخطوط. |
| clear_font_encs() | يمسح قائمة ترميز الخطوط |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

