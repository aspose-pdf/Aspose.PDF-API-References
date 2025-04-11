---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: خاصية الخط. تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تلقائيًا أن يكون مجموعة فرعية ومدمجة
type: docs
weight: 70
url: /ar/net/aspose.pdf.text/font/issubset/
---
## خاصية Font.IsSubset

تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تلقائيًا أن يكون مجموعة فرعية ومدمجة

```csharp
public bool IsSubset { get; set; }
```

## أمثلة

المثال يوضح كيفية البحث عن نص في الصفحة الأولى والحصول على القيمة التي تشير إلى ما إذا كان الخط مجموعة فرعية.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)