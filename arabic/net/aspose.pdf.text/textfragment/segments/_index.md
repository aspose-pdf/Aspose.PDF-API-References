---
title: "TextFragment.Segments"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragment. تحصل على أجزاء النص للمقاطع الحالية من TextFragment"
type: docs
weight: 120
url: /ar/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

يحصل على أجزاء النص للمقاطع الحالية من [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## ملاحظات

باختصار، كائنات [`TextSegment`](../../textsegment/) هي أبناء كائن [`TextFragment`](../). قد يتمكن المستخدمون المتقدمون من الوصول إلى الأجزاء مباشرةً لتنفيذ سيناريوهات تحرير نص أكثر تعقيدًا. للحصول على تفاصيل، يرجى الاطلاع على وصف كائن [`TextFragment`](../).

## أمثلة

يوضح المثال كيفية التنقل بين جميع كائنات [`TextSegment`](../../textsegment/) داخل [`TextFragment`](../).

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تنقل بين جميع أجزاء النص وأخرج نصها ومعلومات موقعها
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


