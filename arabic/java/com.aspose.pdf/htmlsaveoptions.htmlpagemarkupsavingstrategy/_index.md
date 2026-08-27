---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "قد يحتوي نتيجة التحويل على صفحة أو عدة صفحات HTML (التي يمكنها أيضًا الإشارة إلى ملفات خارجية مثل الصور أو الخطوط). يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من."
type: docs
weight: 2110
url: /ar/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

قد يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML (التي قد تشير أيضًا إلى ملفات خارجية مثل الصور أو الخطوط). يمكنك تعيين لهذه الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ معالجة صفحة HTML التي تم إنشاؤها أثناء التحويل (HTML نفسه). في هذه الحالة يمكن إجراء المعالجة (مثل الحفظ إلى تدفق أو قرص) في ذلك الكود المخصص. يجب تنفيذ جميع الإجراءات اللازمة لحفظ علامات صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يُستخدم. إذا كان يجب، لسبب ما، أن تُجرى المعالجة في كود المحول نفسه وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغيّر معلمة 'htmlSavingInfo' داخل الكود المخصص: فهي تُشير إلى المحول بأن جميع الخطوات الضرورية لمعالجة هذا المورد يجب أن تُنفّذ في المحول نفسه كما لو لم يكن هناك أي كود حفظ مخصص خارجي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | طريقة beginInvoke الداخلية |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | طريقة endInvoke الداخلية |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | الطريقة المستدعاة |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
طريقة beginInvoke الداخلية

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
طريقة endInvoke الداخلية

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
الطريقة المستدعاة
