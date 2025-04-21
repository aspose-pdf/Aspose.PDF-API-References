---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: نتيجة التحويل يمكن أن تحتوي على صفحة HTML واحدة أو عدة صفحات HTML يمكن أن تشير أيضًا إلى ملفات خارجية مثل الصور أو الخطوط. يمكنك تعيين هذه الخاصية إلى مفوض تم إنشاؤه من طريقة مخصصة تقوم بمعالجة صفحة HTML التي تم إنشاؤها أثناء التحويل. في هذه الحالة، يمكن إجراء المعالجة مثل الحفظ في دفق أو قرص في هذا الرمز المخصص. في هذه الحالة، يجب اتخاذ جميع الإجراءات اللازمة لحفظ ترميز صفحات HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون قيد الاستخدام. إذا كانت المعالجة لهذه الحالة أو تلك لأي سبب يجب أن تتم بواسطة كود المحول نفسه، وليس في كود مخصص، يرجى تعيين في كود مخصص علامة 'CustomProcessingCancelled' لمتغير معلمة 'htmlSavingInfo' إنها تشير إلى المحول أن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود حفظ مخصص خارجي.
type: docs
weight: 5680
url: /ar/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

نتيجة التحويل يمكن أن تحتوي على صفحة HTML واحدة أو عدة صفحات HTML (التي يمكن أن تشير أيضًا إلى ملفات خارجية مثل الصور أو الخطوط). يمكنك تعيين هذه الخاصية إلى مفوض تم إنشاؤه من طريقة مخصصة تقوم بمعالجة صفحة HTML (HTML نفسها) التي تم إنشاؤها أثناء التحويل. في هذه الحالة، يمكن إجراء المعالجة (مثل الحفظ في دفق أو قرص) في هذا الرمز المخصص. في هذه الحالة، يجب اتخاذ جميع الإجراءات اللازمة لحفظ ترميز صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون قيد الاستخدام. إذا كانت المعالجة لهذه الحالة أو تلك لأي سبب يجب أن تتم بواسطة كود المحول نفسه، وليس في كود مخصص، يرجى تعيين في كود مخصص علامة 'CustomProcessingCancelled' لمتغير معلمة 'htmlSavingInfo': إنها تشير إلى المحول أن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود حفظ مخصص خارجي.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | يمثل البيانات التي يمكن استخدامها لحفظ أو معالجة صفحة HTML المقدمة |

### See Also

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)