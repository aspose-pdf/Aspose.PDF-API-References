---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.FontRepository. تقوم بإجراء بحث عن الخطوط. تبحث في الخطوط المثبتة في النظام وخطوط Pdf القياسية. كما توفر وظيفة لفتح الخطوط المخصصة
type: docs
weight: 10540
url: /ar/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

تقوم بإجراء بحث عن الخطوط. تبحث في الخطوط المثبتة في النظام وخطوط Pdf القياسية. كما توفر وظيفة لفتح الخطوط المخصصة.

```csharp
public sealed class FontRepository
```

## Constructors

| Name | Description |
| --- | --- |
| [FontRepository](fontrepository/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | يحصل على مجموعة مصادر الخطوط. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | يحصل على مجموعة استراتيجيات استبدال الخطوط. |

## Methods

| Name | Description |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | يبحث ويعيد الخط بالاسم المحدد. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | يبحث ويعيد الخط بالاسم المحدد مع تجاهل أو احترام حساسية الحالة. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | يبحث ويعيد الخط بالاسم المحدد ونمط الخط. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | يبحث ويعيد الخط بالاسم المحدد ونمط الخط مع تجاهل أو احترام حساسية الحالة. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | يحمل الخطوط المثبتة في النظام وخطوط Pdf القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي، يتم تحميل الخطوط عند أول طلب لأي خط. استخدام هذه الطريقة يحمل الخطوط النظامية وخطوط Pdf القياسية على الفور قبل فتح أي مستند Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | يفتح الخط بالمسار المحدد لملف الخط. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | يفتح الخط بتدفق الخط المحدد. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | يفتح الخط بالمسار المحدد لملف الخط ومسار ملف القياسات. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | يعيد تحميل جميع الخطوط المحددة بواسطة الخاصية [`Sources`](./sources/) |

## Examples

المثال يوضح كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)