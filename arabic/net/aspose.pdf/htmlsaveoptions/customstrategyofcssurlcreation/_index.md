---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "حقل HtmlSaveOptions. يمكن لهذا الحقل أن يحتوي على طريقة مخصصة تُعيد URL أو قالب URL إذا كان توليد الصفحات المتعددة مفعلاً؛ راجع التفاصيل أدناه حول CSS المطلوب وضعه في HTML الناتج. على سبيل المثال، إذا كنت تريد أن يضع المحول URL محدد بدلاً من اسم ملف CSS القياسي في CSS المُولد، فيجب عليك إنشاء وإدراج طريقة في هذه الخاصية تُولّد URL المطلوب. إذا تم تعيين العلامة SplitCssIntoPages، يجب على هذه الاستراتيجية المخصصة، إن وجدت، أن تُعيد ليس URL محدد للـ CSS بل قالب نص يُستبدل فيه العنصر النائب برقم الصفحة باستخدام دالة string.Format داخل المحول لتتحول إلى URL لملف CSS الخاص بهذه الصفحة أو تلك الصفحة. أمثلة على النص المتوقع إرجاعه في مثل هذه الحالة هي SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /ar/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

يمكن لهذا الحقل أن يحتوي على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد متعدد الصفحات مفعَّلًا - راجع التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولَّد. على سبيل المثال، إذا كنت تريد أن يضع المحول عنوان URL محدد بدلاً من اسم ملف CSS القياسي في CSS المُولَّد، فيجب عليك إنشاء ووضع في هذا الخاصية طريقة تُولِّد عنوان URL المرغوب. إذا تم تعيين العلامة 'SplitCssIntoPages'، يجب على هذه الاستراتيجية المخصصة (إن وجدت) أن تُعيد ليس عنوان URL دقيق للـ CSS بل قالب سلسلة يُستبدل فيه العنصر النائب برقم الصفحة باستخدام دالة string.Format() داخل المحول، بحيث يمكن تحويله إلى عنوان URL لملف CSS الخاص بهذه الصفحة أو تلك الصفحة. أمثلة على سلسلة الإرجاع المتوقعة في هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### انظر أيضًا

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


