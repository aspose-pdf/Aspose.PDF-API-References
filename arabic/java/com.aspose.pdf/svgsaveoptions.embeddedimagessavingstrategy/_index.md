---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "إلى خاصية من هذا النوع يمكنك تعيين مندوب تم إنشاؤه من طريقة مخصصة تنفّذ معالجة حفظ الصورة الخارجية التي تم استخراجها من SVG تم إنشاؤه من PDF."
type: docs
weight: 4730
url: /ar/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

إلى خاصية من هذا النوع يمكنك تعيين مفوض تم إنشاؤه من طريقة مخصصة تنفّذ معالجة حفظ الصورة الخارجية التي تم استخراجها من SVG تم إنشاؤه من PDF ويجب حفظها كموارد خارجية أثناء تحويل PDF إلى HTML. في هذه الحالة يمكن إجراء المعالجة (مثل الحفظ اليدوي إلى تدفق أو إلى قرص) في تلك الشيفرة المخصصة ويجب على تلك الشيفرة المخصصة إرجاع مسار (أو أي سلسلة أخرى بدون علامات اقتباس) سيتم دمجه لاحقًا في SVG المُولَّد بدلاً من المسار الأصلي المفترض لتلك الصورة. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ الصورة في كود الطريقة المقدَّمة، لأن حفظ النتيجة في كود المحول لن يُستخدم. إذا كان يجب معالجة هذا أو ذاك الملف لسبب ما بواسطة كود المحول نفسه، وليس في الشيفرة المخصصة، يرجى تعيين في الشيفرة المخصصة العلامة 'CustomProcessingCancelled' لمتغيّر معلمة 'imageSavingInfo'. هذا يُشير إلى المحول بأن جميع الخطوات الضرورية لمعالجة ذلك المورد يجب أن تُنفَّذ في المحول نفسه كما لو لم يكن هناك أي شيفرة مخصصة خارجية.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
