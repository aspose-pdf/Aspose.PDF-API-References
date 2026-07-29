---
title: "الفئة TextSearchOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Text.TextSearchOptions class. تمثل خيارات البحث عن النص"
type: docs
weight: 11230
url: /ar/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

يمثل خيارات بحث النص

```csharp
public sealed class TextSearchOptions : TextOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | ينشئ مثالا جديدا لكائن `TextSearchOptions`. يحدد وضع استخدام التعبير النمطي. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | ينشئ مثالا جديدا لكائن `TextSearchOptions`. يحدد المستطيل الذي يحد النص المُبحث عنه. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | ينشئ مثالا جديدا لكائن `TextSearchOptions`. يحدد المستطيل الذي يحد النص المُبحث عنه ووضع استخدام التعبير النمطي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | الحصول أو الضبط إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتجاهلها ماص النص (الجزء). true - يعني أن أخطاء غياب الخط ستُتجاهل. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (default) - سيؤدي خطأ غياب الخط إلى إنهاء المعالجة برمي استثناء. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | الحصول أو الضبط إشارة إلى أن أجزاء النص التي تمثل ظل النص العادي سيتجاهلها أثناء البحث. true - يعني أن نص الظل لن يُعثر عليه (جرّب هذا إذا كان بحث النص يُعيد أجزاء مكررة في المواقع القريبة). false - يعني أن نص الظل سيُعثر عليه بالإضافة إلى النص العادي (القيمة الافتراضية). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | الحصول أو الضبط إشارة إلى أن التعبير النمطي يُستخدم. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | الحصول أو الضبط إشارة إلى أن النص يُبحث ضمن حدود الصفحة. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | الحصول أو الضبط إشارة إلى أن أخطاء استخراج النص (فك الترميز) ستُسجل في ماص النص (الجزء). true - يعني أن أخطاء استخراج النص (فك الترميز) ستُسجل. قد يقلل ذلك من الأداء. false (default) - لا تسجيل للأخطاء. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | الحصول أو الضبط المستطيل الذي يحد النص المُبحث عنه. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | الحصول أو الضبط قيمة تسمح بالبحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية، إلخ) أثناء بحث النص. true - سيتم تنفيذ البحث عن الرسومات المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد توجد في المستند الأصلي. اضبط هذا في حالة وجود مشاكل في الأداء أو عدم الحاجة للتعامل مع التسطير أو الخلفية أو القص. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | الحصول أو الضبط قيمة تسمح بالبحث عن النص في Annotations. true - سيُبحث النص في Annotations. false - لن يتم تحليل النص في Annotations بواسطة TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | الحصول أو الضبط قيمة تحدد عدد العناصر الرسومية المتعلقة بالنص (التسطير، الخلفية، إلخ) التي يُسمح بالبحث عنها في الصفحة. القيمة الافتراضية هي 250. اضبط قيمة أقل في حالة مشاكل الأداء، جرّب قيمة أكبر إذا لم يتم العثور على بعض العناصر الرسومية. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | الحصول أو الضبط إشارة إلى أن النص سيُبحث باستخدام ترميز محرك الخط. true - يعني أن ترميز محرك الخط سيُستخدم (جرّب هذا إذا فشل بحث النص بسبب ترميز غير كامل في المستند). false - يعني أن ترميز خط المستند سيُستخدم (القيمة الافتراضية). |

### انظر أيضًا

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


