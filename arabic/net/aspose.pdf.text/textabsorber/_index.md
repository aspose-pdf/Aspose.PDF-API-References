---
title: "الفئة TextAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TextAbsorber. تمثل كائن ماص للنص. تقوم باستخراج النص وتوفر الوصول إلى النتيجة عبر كائن Text."
type: docs
weight: 10980
url: /ar/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

تمثل كائن ماص للنص. تقوم باستخراج النص وتوفر الوصول إلى النتيجة عبر كائن [`Text`](./text/).

```csharp
public class TextAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | ينشئ نسخة جديدة من `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | ينشئ نسخة جديدة من `TextAbsorber` مع خيارات الاستخراج. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | ينشئ نسخة جديدة من `TextAbsorber` مع خيارات البحث عن النص. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | ينشئ نسخة جديدة من `TextAbsorber` مع خيارات الاستخراج والبحث عن النص. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | قائمة من كائنات [`TextExtractionError`](../textextractionerror/). تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | يحصل أو يعيّن خيارات استخراج النص. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | يحصل على النص المستخرج الذي يقوم `TextAbsorber` باستخراجه من مستند PDF أو Page. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | يحصل أو يعيّن خيارات بحث النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | يستخرج النص من الـ document المحدد |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | يستخرج النص من الـ page المحدد |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | يستخرج النص على الـ XForm المحدد. |

## ملاحظات

يُستخدم كائن `TextAbsorber` لاستخراج النص من Pdf document أو page الـ document.

## أمثلة

يوضح المثال كيفية استخراج النص من الصفحة الأولى لـ PDF document.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الماصة للصفحة الأولى
doc.Pages[1].Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


