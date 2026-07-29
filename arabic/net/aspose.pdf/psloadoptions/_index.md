---
title: "فئة PsLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.PsLoadOptions. تمثل الخيارات لتحميل/استيراد ملف .mhtfile إلى مستند pdf."
type: docs
weight: 9880
url: /ar/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

يمثل خيارات التحميل/الاستيراد لملف .mht إلى مستند PDF.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | يحدد ما إذا كان سيتم حفظ الخطوط غير TrueType إلى TTF. يقلل ذلك بشكل كبير من حجم المستند الناتج في تحويل PS إلى PDF ويزيد من سرعة تحويل ملفات PS التي تحتوي على كمية كبيرة من النص بخطوط غير TrueType إلى أي تنسيق إخراج. ومع ذلك، هناك إزاحة عمودية صغيرة للنص عند تحويل ملف PostSctipt إلى صورة. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | يحصل أو يعيّن مسارات مجلدات الخطوط. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


