---
title: "فئة ParagraphAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Text.ParagraphAbsorber. تمثل كائن ماص للكيانات الهيكلية للصفحة مثل الأقسام والفقرات. تقوم بالبحث عن الأقسام والفقرات في النص وتوفر الوصول إلى المستطيلات والمتعددات التي تصفه في مساحة إحداثيات النص. كما تقوم بالبحث عن مقاطع النص وتوفر الوصول إلى نتائج البحث عبر مجموعات TextFragments المجمعة حسب عناصر الهيكل."
type: docs
weight: 10850
url: /ar/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

يمثل كائن ماص لكائنات بنية الصفحة مثل الأقسام والفقرات. يجري بحثًا عن الأقسام والفقرات النصية ويوفر الوصول إلى المستطيلات والمتعددات التي تصفها في فضاء إحداثيات النص. كما يجري بحثًا عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات !:TextFragments المجمعة حسب عناصر البنية.

```csharp
public class ParagraphAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | ينشئ مثلاً جديداً من `ParagraphAbsorber` الذي يقوم بالبحث عن أقسام/فقرات المستند أو الصفحة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | ينشئ مثلاً جديداً من `ParagraphAbsorber` الذي يقوم بالبحث عن أقسام/فقرات المستند أو الصفحة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | ينشئ مثلاً جديداً من `ParagraphAbsorber` الذي يقوم بالبحث عن أقسام/فقرات المستند أو الصفحة باستخدام المعلمات المحددة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | ينشئ مثلاً جديداً من `ParagraphAbsorber` الذي يقوم بالبحث عن أقسام/فقرات المستند أو الصفحة باستخدام المعلمات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | يحصل أو يضبط القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص البداية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | يحصل على مجموعة من [`PageMarkup`](../pagemarkup/) التي تم امتصاصها. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | يحصل أو يعيّن ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | يحصل أو يعيّن القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقياً (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عمودياً (الأعمدة). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | يحصل أو يعيّن TextReplaceOptions. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | يقوم بالبحث عن الأقسام والفقرات في الـ[`Document`](../../aspose.pdf/document/) المحدد. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | يقوم بالبحث في الـ[`Page`](../../aspose.pdf/page/) المحدد. |

## ملاحظات

عند اكتمال البحث، ستحتوي مجموعة [`PageMarkups`](./pagemarkups/) على كائنات [`PageMarkup`](../pagemarkup/) التي تمثل هيكل الصفحة عبر مجموعات [`MarkupSection`](../markupsection/) و[`MarkupParagraph`](../markupparagraph/). يوفر كائن [`TextFragment`](../textfragment/) الوصول إلى نص نتيجة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

## أمثلة

يوضح المثال كيفية العثور على أول مقطع نصي لكل فقرة في الصفحة الأولى من مستند PDF وتظليله.

```csharp
// فتح المستند
Document doc = new Document("input.pdf");

// إنشاء كائن ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// قبول الماص للصفحة الأولى
absorber.Visit(doc.Pages[1]);

// احصل على كائن العلامات للصفحة الأولى
PageMarkup markup = absorber.PageMarkups[0];

// تجول عبر عناصر بنية نص الصفحة للعثور على أول مقطع نصي في كل فقرة
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // تحديث خصائص النص
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// حفظ المستند
doc.Save(GetOutputPath("output.pdf"));
```

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


