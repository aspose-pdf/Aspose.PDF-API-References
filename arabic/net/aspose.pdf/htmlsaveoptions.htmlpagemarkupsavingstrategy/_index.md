---
title: "المندوب HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML يمكنها أيضًا الإشارة إلى ملفات خارجية مثل الصور أو الخطوط. يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفذ معالجة HTMLpageHTML التي تم إنشاؤها أثناء التحويل. في هذه الحالة يمكن تنفيذ المعالجة مثل الحفظ في تدفق أو قرص في ذلك الكود المخصص. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ علامات صفحات HTML في كود الطريقة الموردة لأن حفظ النتيجة في كود المحول لن يكون مستخدمًا. إذا كان يجب تنفيذ المعالجة لهذه الحالة أو لتلك الحالة لسبب ما بواسطة كود المحول نفسه وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغير معلمات 'htmlSavingInfo'؛ فهي تشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة هذا المورد يجب أن تُنفذ في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود حفظ مخصص خارجي."
type: docs
weight: 5810
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML (يمكنها أيضًا الإشارة إلى ملفات خارجية مثل الصور أو الخطوط). يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفذ معالجة HTML-page(HTML نفسها) التي تم إنشاؤها أثناء التحويل. في هذه الحالة يمكن تنفيذ المعالجة (مثل الحفظ في تدفق أو قرص) في ذلك الكود المخصص. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ علامات صفحة HTML في كود الطريقة الموردة، لأن حفظ النتيجة في كود المحول لن يكون مستخدمًا. إذا كان يجب تنفيذ المعالجة لهذه الحالة أو لتلك الحالة لسبب ما بواسطة كود المحول نفسه، وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغير معلمة 'htmlSavingInfo'؛ فهي تشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة هذا المورد يجب أن تُنفذ في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود حفظ مخصص خارجي.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | يمثل البيانات التي يمكن استخدامها لحفظ أو معالجة صفحة HTML الموردة |

### انظر أيضًا

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


