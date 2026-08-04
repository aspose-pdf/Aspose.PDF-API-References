---
title: "EpubLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يحتوي على خيارات لتحميل/استيراد ملف EPUB إلى مستند PDF"
type: docs
weight: 310
url: /ar/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

يحتوي على خيارات لتحميل/استيراد ملف EPUB إلى مستند PDF

يعرض نوع EpubLoadOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| EpubLoadOptions() | ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند PDF. <br/>            حجم صفحة PDF الافتراضي - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | يُهيئ نسخة جديدة من فئة EpubLoadOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| warning_handler | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. <br/>            تُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. <br/>            Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم أيضًا Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |
| load_format | يمثل تنسيق الملف الذي تصفه [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_size | يحصل أو يعيّن حجم صفحة الإخراج للاستيراد. |
| margin | يحصل على مرجع للكائن الذي يمثل معلومات الهوامش. |
| margins_area_usage_mode | يمثل وضع استخدام مساحة الهوامش - يحدد معالجة <br/>              التعليمات (إن وجدت) في CSS للمستند المستورد<br/>              المتعلقة باستخدام الهوامش. |
| page_size_adjustment_mode | انتباه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى واجهة برمجة التطبيقات العامة بسبب مشكلة عائق في <br/>              طبقة OSHARED تم اكتشافها في المستند النموذجي.<br/>              <br/>             <br/>              يمثل وضع استخدام حجم الصفحة أثناء التحويل.<br/>             الصيغ (مثل HTML، EPUB وغيرها) عادةً ما تكون ذات تصميم عائم، لذا يسمح بتناسب حجم الصفحة المطلوب<br/>             . ولكن أحيانًا يكون للمحتوى مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب.<br/>               في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع <br/>             حجم الصفحة الأولي المطلوب لوثيقة PDF الناتجة). |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

