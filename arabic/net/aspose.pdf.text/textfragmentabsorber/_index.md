---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber class. يمثل كائن ماص لقطع النص. يقوم بإجراء بحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة TextFragments
type: docs
weight: 10950
url: /ar/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

يمثل كائن ماص لقطع النص. يقوم بإجراء بحث عن النص ويوفر الوصول إلى نتائج البحث عبر [`TextFragments`](./textfragments/) المجموعة.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | يقوم بتهيئة مثيل جديد من `TextFragmentAbsorber` الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لكائن فئة System.Text.RegularExpressions.Regex المحدد. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | يقوم بتهيئة مثيل جديد من `TextFragmentAbsorber` مع خيارات تحرير النص، الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة وخيارات بحث النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة وخيارات بحث النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة وخيارات تحرير النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة وخيارات بحث النص. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | يقوم بتهيئة مثيل جديد من فئة `TextFragmentAbsorber` لعبارة النص المحددة، خيارات بحث النص وخيارات تحرير النص. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | قائمة من كائنات [`TextExtractionError`](../textextractionerror/) . تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كانت TextSearchOptions.LogTextExtractionErrors = true; وقد يقلل ذلك من الأداء. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | يحصل أو يحدد خيارات استخراج النص. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | القيمة تشير إلى ما إذا كانت الأخطاء قد وجدت أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كانت TextSearchOptions.LogTextExtractionErrors = true; وقد يقلل ذلك من الأداء. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | يحصل أو يحدد العبارة التي يبحث عنها `TextFragmentAbsorber` في مستند PDF أو الصفحة. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | يحصل على قاموس من حالات البحث التي يتم تقديمها مع فئة System.Text.RegularExpressions.Regex كمفتاح و [`TextFragment`](../textfragment/) كقيمة. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | يحصل على النص المستخرج الذي يقوم به [`TextAbsorber`](../textabsorber/) في مستند PDF أو الصفحة. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | يحصل أو يحدد خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | يحصل على مجموعة من حالات البحث التي يتم تقديمها مع كائنات [`TextFragment`](../textfragment/) . |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | يحصل أو يحدد خيارات استبدال النص. تحدد الخيارات السلوك عندما يتم استبدال نص القطعة بنص أقصر/أطول. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | يحصل أو يحدد خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات العادية. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | يطبق حجم الخط لجميع مقاطع النص التي تم امتصاصها. يعمل بشكل أسرع من التكرار عبر المقاطع إذا تم امتصاص جميع المقاطع في الصفحة (الصفحات). خلاف ذلك، يعمل بشكل مشابه مع التكرار. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | يطبق الخط لجميع مقاطع النص التي تم امتصاصها. يعمل بشكل أسرع من التكرار عبر المقاطع إذا تم امتصاص جميع المقاطع في الصفحة (الصفحات). خلاف ذلك، يعمل بشكل مشابه مع التكرار. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | يطبق الخط والحجم لجميع مقاطع النص التي تم امتصاصها. يعمل بشكل أسرع من التكرار عبر المقاطع إذا تم امتصاص جميع المقاطع في الصفحة (الصفحات). خلاف ذلك، يعمل بشكل مشابه مع التكرار. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | يزيل جميع النصوص من المستند. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | يزيل جميع النصوص من الصفحة المحددة. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | يزيل النص داخل المستطيل المحدد من الصفحة المحددة. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | يمسح مجموعة TextFragments من كائن `TextFragmentAbsorber` هذا. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | يقوم بإجراء بحث على المستند المحدد. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | يقوم بإجراء بحث على الصفحة المحددة. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | يقوم بإجراء بحث على كائن النموذج المحدد. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | يستخرج النص على XForm المحدد. |

## Remarks

كائن `TextFragmentAbsorber` يستخدم أساسًا في سيناريو بحث النص. عند الانتهاء من البحث، يتم تمثيل الحالات مع كائنات [`TextFragment`](../textfragment/) التي تحتوي عليها مجموعة [`TextFragments`](./textfragments/). يوفر كائن [`TextFragment`](../textfragment/) الوصول إلى نص حالة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

## Examples

المثال يوضح كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص وخطه.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)