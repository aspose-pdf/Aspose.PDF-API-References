---
title: "MobiXmlSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "خيارات الحفظ للتصدير إلى تنسيق Xml"
type: docs
weight: 960
url: /ar/python-net/aspose.pdf/mobixmlsaveoptions/
---

## MobiXmlSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق Xml

يعرض نوع MobiXmlSaveOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| MobiXmlSaveOptions() | ينشئ مثيلاً جديداً من فئة MobiXmlSaveOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| warning_handler | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. <br/>            يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. <br/>            Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم أيضًا Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |
| save_format | تنسيق حفظ البيانات. |
| close_response | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة. |
| extract_ocr_sublayer_only | هذا السمة تُفعِّل الوظيفة لاستخراج الصورة أو النص <br/>            لمستندات PDF التي تحتوي على طبقة فرعية OCR. |
| try_merge_adjacent_same_background_images | أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول)<br/>              مُنشأة من عدة صور خلفية متكررة متماثلة موضوعة بجوار بعضها.<br/>              في مثل هذه الحالة قد تُنشئ عارضات الصيغ المستهدفة (مثلاً MsWord لصيغة DOCS) حدودًا مرئية بين أجزاء صور الخلفية،<br/>              بسبب اختلاف تقنيات تنعيم حواف الصورة (anti-aliasing) عن Acrobat Reader.<br/>               إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين <br/>              أجزاء صور الخلفية المتماثلة، يرجى محاولة استخدام هذا الإعداد للتخلص <br/>              من هذا التأثير غير المرغوب. <br/>                انتباه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء عملية التحويل بشكل كبير،<br/>              لذا، يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

