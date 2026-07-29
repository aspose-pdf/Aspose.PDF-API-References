---
title: "الفئة FontRepository"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.FontRepository. تقوم بالبحث عن الخطوط. تبحث في الخطوط المثبتة على النظام وخطوط Pdf القياسية. كما توفر وظيفة لفتح الخطوط المخصصة."
type: docs
weight: 10720
url: /ar/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

يجري بحثًا عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط Pdf القياسية. كما يوفر وظيفة لفتح الخطوط المخصصة.

```csharp
public sealed class FontRepository
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FontRepository](fontrepository/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | يحصل على مجموعة مصادر الخطوط. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | يحصل على مجموعة استراتيجيات استبدال الخطوط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | يبحث ويعيد الخط بالاسم المحدد. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | يبحث ويعيد الخط بالاسم المحدد متجاهلاً أو مع احترام حساسية الحالة. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | يبحث ويعيد الخط بالاسم المحدد ونمط الخط. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | يبحث ويعيد الخط بالاسم المحدد ونمط الخط متجاهلاً أو مع احترام حساسية الحالة. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | يقوم بتحميل الخطوط المثبتة على النظام وخطوط Pdf القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي يتم تحميل الخطوط عند الطلب الأول لأي خط. استخدام هذه الطريقة يحمل خطوط النظام وخطوط Pdf القياسية فورًا قبل فتح أي مستند Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | يفتح الخط باستخدام مسار ملف الخط المحدد. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | يفتح الخط باستخدام تدفق الخط المحدد. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | يفتح الخط باستخدام مسار ملف الخط ومسار ملف المقاييس المحدد. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | يعيد تحميل جميع الخطوط المحددة بواسطة الخاصية [`Sources`](./sources/) |

## أمثلة

يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// العثور على الخط
Font font = FontRepository.FindFont("Arial");

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


