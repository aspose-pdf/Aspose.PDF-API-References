---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.ParagraphAbsorber. تمثل كائن ماص لأشياء هيكل الصفحة مثل الأقسام والفقرات. يقوم بالبحث عن الأقسام والفقرات النصية ويوفر الوصول إلى المستطيلات والأشكال المتعددة التي تصفها في فضاء إحداثيات النص. كما يقوم أيضًا بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات TextFragments المجمعة حسب عناصر الهيكل.
type: docs
weight: 10670
url: /ar/net/aspose.pdf.text/paragraphabsorber/
---
## فئة ParagraphAbsorber

تمثل كائن ماص لأشياء هيكل الصفحة مثل الأقسام والفقرات. يقوم بالبحث عن الأقسام والفقرات النصية ويوفر الوصول إلى المستطيلات والأشكال المتعددة التي تصفها في فضاء إحداثيات النص. كما يقوم أيضًا بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر !:TextFragments المجمعة حسب عناصر الهيكل.

```csharp
public class ParagraphAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | يقوم بتهيئة مثيل جديد من `ParagraphAbsorber` الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | يقوم بتهيئة مثيل جديد من `ParagraphAbsorber` الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | يقوم بتهيئة مثيل جديد من `ParagraphAbsorber` الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة مع المعلمات المحددة. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | يقوم بتهيئة مثيل جديد من `ParagraphAbsorber` الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة مع المعلمات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | يحصل أو يحدد القيمة التي تشير إلى ما إذا كانت خطوط النص التي تبدأ في قسم جديد يمكن اعتبارها استمرارًا للفقرة الأخيرة من القسم السابق. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | يحصل على مجموعة من [`PageMarkup`](../pagemarkup/) التي تم امتصاصها. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | يحصل أو يحدد خيارات ParagraphAbsorber. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | يحصل أو يحدد القيمة التي تو instructs عدد مرات البحث المتسلسل عن عناصر الهيكل الأكثر دقة. عمق البحث الافتراضي هو 3. وهذا يعني ثلاث عمليات بحث عن الأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث عن الأقسام المقسمة عموديًا (الأعمدة). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | يحصل أو يحدد خيارات TextReplace. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | يقوم بالبحث عن الأقسام والفقرات في [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | يقوم بالبحث في [`Page`](../../aspose.pdf/page/). |

## ملاحظات

عند الانتهاء من البحث، ستحتوي مجموعة [`PageMarkups`](./pagemarkups/) على كائنات [`PageMarkup`](../pagemarkup/) التي تمثل هيكل الصفحة من خلال مجموعات [`MarkupSection`](../markupsection/) و[`MarkupParagraph`](../markupparagraph/). يوفر كائن [`TextFragment`](../textfragment/) الوصول إلى نص حدوث البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

## أمثلة

توضح المثال كيفية العثور على أول مقطع نصي من كل فقرة في الصفحة الأولى من مستند PDF وتظليله.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)