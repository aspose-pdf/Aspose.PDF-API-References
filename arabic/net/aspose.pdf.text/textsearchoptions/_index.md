---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextSearchOptions. تمثل خيارات بحث النص
type: docs
weight: 11040
url: /ar/net/aspose.pdf.text/textsearchoptions/
---
## فئة خيارات بحث النص

تمثل خيارات بحث النص

```csharp
public sealed class TextSearchOptions : TextOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | يقوم بتهيئة مثيل جديد من كائن `TextSearchOptions`. يحدد وضع استخدام التعبير العادي. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | يقوم بتهيئة مثيل جديد من كائن `TextSearchOptions`. يحدد المستطيل الذي يحدد النص الذي سيتم البحث عنه. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | يقوم بتهيئة مثيل جديد من كائن `TextSearchOptions`. يحدد المستطيل الذي يحدد النص الذي سيتم البحث عنه ووضع استخدام التعبير العادي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | يحصل أو يحدد الإشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها بواسطة ماص النص (الجزء). true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (افتراضي) - ستؤدي أخطاء غياب الخط إلى إنهاء المعالجة بإلقاء استثناء. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | يحصل أو يحدد الإشارة إلى أن مقاطع النص التي تمثل ظل النص العادي سيتم تجاهلها أثناء البحث. true - يعني أن النص الظلي لن يتم العثور عليه (جرب هذا إذا كانت عملية بحث النص تعيد مقاطع مكررة في مواقع قريبة) false - يعني أن النص الظلي سيتم العثور عليه بالإضافة إلى النص العادي (القيمة الافتراضية) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | يحصل أو يحدد الإشارة إلى أنه يتم استخدام التعبير العادي. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | يحصل أو يحدد الإشارة إلى أنه يتم البحث عن النص داخل حدود الصفحة. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | يحصل أو يحدد الإشارة إلى أن أخطاء استخراج النص (فك التشفير) سيتم تسجيلها في ماص النص (الجزء). true - يعني أن أخطاء استخراج النص (فك التشفير) سيتم تسجيلها. قد يؤدي ذلك إلى تقليل الأداء. false (افتراضي) - لا يوجد تسجيل للأخطاء. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | يحصل أو يحدد المستطيل الذي يحدد النص الذي سيتم البحث عنه. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | يحصل أو يحدد القيمة التي تسمح بالبحث عن الرسوم البيانية المتعلقة بالنص (التسطير، الخلفية، إلخ) أثناء بحث النص. true - سيتم إجراء البحث عن الرسوم البيانية المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد تكون موجودة في المستند المصدر. قم بتعيين هذا في حالة وجود مشاكل في الأداء أو عدم الحاجة للتعامل مع التسطير أو الخلفية أو القص. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | يحصل أو يحدد القيمة التي تسمح بالبحث عن النص في التعليقات. true - سيتم البحث عن النص في التعليقات. false - لن يتم تحليل النص في التعليقات بواسطة ماص النص. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | يحصل أو يحدد القيمة التي تحد من البحث عن الرسوم البيانية المتعلقة بالنص (التسطير، الخلفية، إلخ) على الصفحة لعدد محدد من العناصر. القيمة الافتراضية هي 250. قم بتعيين قيمة أقل في حالة وجود مشاكل في الأداء، جرب قيمة أكبر في حالة عدم العثور على بعض العناصر الرسومية. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | يحصل أو يحدد الإشارة إلى أنه سيتم البحث عن النص باستخدام ترميز محرك الخط. true - يعني أنه سيتم استخدام ترميز محرك الخط (جرب هذا إذا فشلت عملية بحث النص بسبب ترميز غير مثالي في المستند) false - يعني أنه سيتم استخدام ترميز خط المستند (القيمة الافتراضية) |

### انظر أيضًا

* فئة [TextOptions](../textoptions/)
* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)