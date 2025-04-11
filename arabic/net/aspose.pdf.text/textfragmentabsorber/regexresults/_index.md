---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragmentAbsorber. تحصل على قاموس لحدوثات البحث التي يتم تقديمها مع فئة System.Text.RegularExpressions.Regex كمفتاح و TextFragment كقيمة
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## خاصية TextFragmentAbsorber.RegexResults

تحصل على قاموس لحدوثات البحث التي يتم تقديمها مع فئة System.Text.RegularExpressions.Regex كمفتاح و [`TextFragment`](../../textfragment/) كقيمة.

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## أمثلة

يظهر المثال كيفية العثور على نص باستخدام مصفوفة من التعبيرات العادية على الصفحة الأولى من مستند PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### انظر أيضًا

* فئة [TextFragmentCollection](../../textfragmentcollection/)
* فئة [TextFragmentAbsorber](../)
* مساحة الأسماء [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../../)