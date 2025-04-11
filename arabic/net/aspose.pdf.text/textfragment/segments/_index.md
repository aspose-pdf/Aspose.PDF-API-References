---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragment. تحصل على مقاطع النص للـ TextFragment الحالي
type: docs
weight: 120
url: /ar/net/aspose.pdf.text/textfragment/segments/
---
## خاصية TextFragment.Segments

تحصل على مقاطع النص للـ [`TextFragment`](../) الحالي.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## ملاحظات

باختصار، كائنات [`TextSegment`](../../textsegment/) هي أطفال لكائن [`TextFragment`](../). يمكن للمستخدمين المتقدمين الوصول إلى المقاطع مباشرة لأداء سيناريوهات تحرير نص أكثر تعقيدًا. لمزيد من التفاصيل، يرجى الاطلاع على وصف كائن [`TextFragment`](../).

## أمثلة

توضح هذه المثال كيفية التنقل بين جميع كائنات [`TextSegment`](../../textsegment/) داخل [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)