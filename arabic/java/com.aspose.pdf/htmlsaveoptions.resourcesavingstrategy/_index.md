---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمكنك إسناد مُفَوَّض (delegate) تم إنشاؤه من طريقة مخصصة إلى هذه الخاصية، تُنفّذ معالجة المورد الخارجي (خط أو صورة) الذي تم استخراجُه من PDF ويجب حفظه."
type: docs
weight: 2150
url: /ar/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

يمكنك إسناد إلى هذه الخاصية مفوض تم إنشاؤه من طريقة مخصصة تنفّذ معالجة المورد الخارجي (خط أو صورة) الذي تم استخراجها من PDF ويجب حفظه كمورد خارجي أثناء تحويل PDF إلى HTML. في هذه الحالة يمكن تنفيذ المعالجة (مثل الحفظ في تدفق أو على القرص) في ذلك الكود المخصص ويجب على هذا الكود المخصص إرجاع المسار (أو أي سلسلة أخرى بدون علامات اقتباس) التي سيتم دمجها لاحقًا في HTML المُولَّد بدلاً من المسار الأصلي المفترض لتلك الصورة. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ الصورة في شفرة الطريقة المقدَّمة، لأن حفظ النتيجة في شفرة المحول لن يُستَخدم. إذا كان من الضروري لسبب ما أن تتم معالجة هذا الملف أو ذاك الملف بواسطة شفرة المحول نفسها، وليس في الكود المخصص، يرجى تعيين في الكود المخصص العلامة 'CustomProcessingCancelled' لمتغيّر معلمة 'resourceSavingInfo'. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفّذ في المحول نفسه كما لو لم يكن هناك أي كود مخصص خارجي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | الطريقة المستدعاة |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
الطريقة المستدعاة
