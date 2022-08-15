---
title: TextFragmentAbsorber
second_title: Aspose.PDF لمرجع .NET API
description: يمثل كائن ممتص لأجزاء النص. يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبرTextFragments./textfragmentabsorber/textfragments جمع .
type: docs
weight: 7110
url: /ar/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

يمثل كائن ممتص لأجزاء النص. يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](./textfragments) جمع .

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) يقوم بالبحث في جميع أجزاء النص من المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة لكائن فئة System.Text.RegularExpressions.Regex المحدد. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة للعبارة النصية المحددة. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber)مع خيارات تحرير النص ، والتي تقوم بالبحث في جميع أجزاء النص من المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات البحث عن النص. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber)فئة للعبارة النصية المحددة وخيارات البحث عن النص. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات البحث عن النص وخيارات تحرير النص. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | قائمة[`TextExtractionError`](../textextractionerror) أشياء. يحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. وقد يؤدي إلى انخفاض الأداء. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | الحصول على أو تعيين خيارات استخراج النص. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | تشير القيمة إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم إجراء البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true وقد يؤدي إلى انخفاض الأداء. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | الحصول على أو تعيين العبارة التي يحتوي عليها ملف[`TextFragmentAbsorber`](../textfragmentabsorber) عمليات البحث في مستند أو صفحة PDF. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | يحصل على النص المستخرج من ملف[`TextAbsorber`](../textabsorber) مقتطفات من مستند أو صفحة PDF . |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | الحصول على أو تعيين خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما يتعذر كتابة الرمز المطلوب بالخط. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | الحصول على مجموعة من تكرارات البحث التي يتم تقديمها مع[`TextFragment`](../textfragment) الكائنات . |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | الحصول على أو تعيين خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بمزيد من الاختصار / الطويل. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | الحصول على خيارات البحث أو تعيينها. تتيح الخيارات البحث باستخدام التعبيرات العادية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | يطبق حجم الخط على كل أجزاء النص التي تم استيعابها. إنه يعمل بشكل أسرع من التكرار خلال الأجزاء إذا تم امتصاص جميع الأجزاء الموجودة على الصفحة (الصفحات). وإلا فإنه يعمل بشكل مشابه مع الحلقات. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | يطبق الخط على كل أجزاء النص التي تم استيعابها. إنه يعمل بشكل أسرع من التكرار خلال الأجزاء إذا تم امتصاص جميع الأجزاء الموجودة على الصفحة (الصفحات). وإلا فإنه يعمل بشكل مشابه مع الحلقات. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | يطبق الخط والحجم على كل أجزاء النص التي تم استيعابها. إنه يعمل بشكل أسرع من التكرار خلال الأجزاء إذا تم امتصاص جميع الأجزاء الموجودة على الصفحة (الصفحات). وإلا فإنه يعمل بشكل مشابه مع الحلقات. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | يزيل كل النص من المستند. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | يزيل كل النص من الصفحة المحددة. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | يزيل النص الموجود داخل المستطيل المحدد من الصفحة المحددة. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | يمسح مجموعة TextFragments من هذا[`TextFragmentAbsorber`](../textfragmentabsorber) الكائن . |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | يقوم بالبحث في المستند المحدد. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | يقوم بالبحث في الصفحة المحددة . |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | يقوم بالبحث عن كائن النموذج المحدد. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | مقتطفات من النص في XForm المحدد . |

### ملاحظات

ملف[`TextFragmentAbsorber`](../textfragmentabsorber) يتم استخدام الكائن بشكل أساسي في سيناريو البحث عن النص. عند اكتمال البحث ، يتم تمثيل التكرارات بـ[`TextFragment`](../textfragment) الأشياء التي[`TextFragments`](./textfragments) تحتوي المجموعة[`TextFragment`](../textfragment) يوفر الكائن الوصول إلى نص ورود البحث وخصائص النص ويسمح بتحرير النص وتغيير حالة النص (الخط وحجم الخط واللون وما إلى ذلك).

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص والخط.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط عند ظهور النص الأول
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextAbsorber](../textabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
