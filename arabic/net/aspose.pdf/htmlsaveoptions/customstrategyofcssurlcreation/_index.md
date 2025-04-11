---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: حقل HtmlSaveOptions. يمكن أن يحتوي هذا الحقل على طريقة مخصصة تعيد URL أو قالب URL إذا كانت عملية التوليد متعددة الصفحات مفعلة - انظر التفاصيل أدناه لموضوع CSS كما يجب أن يتم وضعه في HTML الناتج. على سبيل المثال، إذا كنت تريد من المحول وضع URL محدد بدلاً من اسم ملف CSS القياسي في CSS الناتج، فيجب عليك فقط إنشاء ووضع في هذه الخاصية طريقة تولد URL المرغوب. إذا تم تعيين علامة 'SplitCssIntoPages'، فيجب أن تعيد هذه الاستراتيجية المخصصة (إن وجدت) ليس URL دقيق لـ CSS ولكن بدلاً من ذلك سلسلة قالب يمكن (بعد استبدال العنصر النائب برقم الصفحة باستخدام دالة string.Format() داخل المحول) أن يتم حلها إلى URL لـ CSS لهذه الصفحة أو تلك. أمثلة على سلسلة الإرجاع المتوقعة في هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')
type: docs
weight: 300
url: /ar/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## حقل HtmlSaveOptions.CustomStrategyOfCssUrlCreation

يمكن أن يحتوي هذا الحقل على طريقة مخصصة تعيد URL (أو قالب URL إذا كانت عملية التوليد متعددة الصفحات مفعلة - انظر التفاصيل أدناه) لموضوع CSS كما يجب أن يتم وضعه في HTML الناتج. على سبيل المثال، إذا كنت تريد من المحول وضع URL محدد بدلاً من اسم ملف CSS القياسي في CSS الناتج، فيجب عليك فقط إنشاء ووضع في هذه الخاصية طريقة تولد URL المرغوب. إذا تم تعيين علامة 'SplitCssIntoPages'، فيجب أن تعيد هذه الاستراتيجية المخصصة (إن وجدت) ليس URL دقيق لـ CSS ولكن بدلاً من ذلك سلسلة قالب يمكن (بعد استبدال العنصر النائب برقم الصفحة باستخدام دالة string.Format() داخل المحول) أن يتم حلها إلى URL لـ CSS لهذه الصفحة أو تلك. أمثلة على سلسلة الإرجاع المتوقعة في هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### انظر أيضًا

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)