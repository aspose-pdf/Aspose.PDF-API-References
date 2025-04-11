---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragmentAbsorber. تحصل على مجموعة من حالات البحث التي يتم تقديمها مع كائنات TextFragment
type: docs
weight: 90
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## خاصية TextFragmentAbsorber.TextFragments

تحصل على مجموعة من حالات البحث التي يتم تقديمها مع [`TextFragment`](../../textfragment/) كائنات.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## أمثلة

المثال يوضح كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال جميع حالات البحث بنص جديد.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)