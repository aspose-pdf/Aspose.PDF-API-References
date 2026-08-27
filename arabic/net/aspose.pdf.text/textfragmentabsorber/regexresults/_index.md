---
title: "TextFragmentAbsorber.RegexResults"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragmentAbsorber. تحصل على القاموس الخاص بحدوث عمليات البحث التي يتم تمثيلها بفئة System.Text.RegularExpressions.Regex كمفتاح و TextFragment كقيمة"
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

تحصل على القاموس الخاص بحدوث عمليات البحث التي يتم تمثيلها بفئة System.Text.RegularExpressions.Regex كمفتاح و [`TextFragment`](../../textfragment/) كقيمة.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## أمثلة

يوضح المثال كيفية العثور على النص باستخدام مصفوفة من التعبيرات النمطية في الصفحة الأولى من PDF Document Page.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// أنشئ كائن TextFragmentAbsorber الذي يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام تعبير نمطي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// احصل على النتائج
var results = absorber.RegexResults;
```

### انظر أيضًا

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


