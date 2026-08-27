---
title: "الفئة TextFragmentAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Text.TextFragmentAbsorber class. تمثل كائن ماص لقطاعات النص. تقوم بالبحث عن النص وتوفر الوصول إلى نتائج البحث عبر مجموعة TextFragments"
type: docs
weight: 11130
url: /ar/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

تمثل كائن ماص لقطاعات النص. تقوم بالبحث عن النص وتوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](./textfragments/) .

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | ينشئ مثيلًا جديدًا من `TextFragmentAbsorber` يقوم بالبحث في جميع قطاعات النص في المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للكائن من فئة System.Text.RegularExpressions.Regex المحدد. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | ينشئ مثيلًا جديدًا من `TextFragmentAbsorber` مع خيارات تحرير النص، يقوم بالبحث في جميع قطاعات النص في المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة وخيارات البحث عن النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة وخيارات البحث عن النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة وخيارات البحث عن النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | ينشئ مثيلًا جديدًا من فئة `TextFragmentAbsorber` للعبارة النصية المحددة، خيارات البحث عن النص، وخيارات تحرير النص. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | قائمة من كائنات [`TextExtractionError`](../textextractionerror/). تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | يحصل أو يعيّن خيارات استخراج النص. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | يحصل أو يعيّن العبارة التي يبحث عنها `TextFragmentAbsorber` في مستند PDF أو الصفحة. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | يحصل على القاموس الخاص بحدوث عمليات البحث التي يتم تمثيلها بفئة System.Text.RegularExpressions.Regex كمفتاح و[`TextFragment`](../textfragment/) كقيمة. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | يحصل على النص المستخرج الذي تقوم [`TextAbsorber`](../textabsorber/) باستخراجه من مستند PDF أو الصفحة. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | يحصل أو يعيّن خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | يحصل على مجموعة حدوث عمليات البحث التي يتم تمثيلها بكائنات [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | يحصل أو يعيّن خيارات استبدال النص. تحدد الخيارات السلوك عندما يتم استبدال نص الجزء إلى أقصر/أطول. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | يحصل أو يعيّن خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | يطبق حجم الخط لجميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء على الصفحة(الصفحات). وإلا يعمل بشكل مشابه مع التكرار. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | يطبق الخط لجميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء على الصفحة(الصفحات). وإلا يعمل بشكل مشابه مع التكرار. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | يطبق الخط والحجم لجميع أجزاء النص التي تم امتصاصها. يعمل أسرع من التكرار عبر الأجزاء إذا تم امتصاص جميع الأجزاء على الصفحة(الصفحات). وإلا يعمل بشكل مشابه مع التكرار. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | يزيل جميع النصوص من المستند. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | يزيل جميع النصوص من الصفحة المحددة. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | يزيل النص داخل المستطيل المحدد من الصفحة المحددة. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | يمسح مجموعة TextFragments لهذا الكائن `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | ينفّذ البحث على المستند المحدد. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | ينفّذ البحث على الصفحة المحددة. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | ينفّذ البحث على كائن النموذج المحدد. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | يستخرج النص على الـ XForm المحدد. |

## ملاحظات

يُستخدم كائن `TextFragmentAbsorber` أساسًا في سيناريو البحث عن النص. عند اكتمال البحث يتم تمثيل الوقائع بكائنات [`TextFragment`](../textfragment/) التي تحتويها مجموعة [`TextFragments`](./textfragments/). يوفر كائن [`TextFragment`](../textfragment/) إمكانية الوصول إلى نص الوقائع، وخصائص النص، ويسمح بتعديل النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF وتبديل النص وخطه.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط لأول تكرار نص
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


