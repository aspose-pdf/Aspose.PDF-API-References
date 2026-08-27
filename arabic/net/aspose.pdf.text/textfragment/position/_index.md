---
title: "TextFragment.Position"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragment. تحصل أو تعيّن موضع النص للنص الممثَّل بواسطة كائن TextFragment."
type: docs
weight: 90
url: /ar/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

يحصل أو يعين موضع النص للنص الممثَّل بكائن [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## أمثلة

يوضح المثال كيفية عرض موضع النص الممثَّل بكائن [`TextFragment`](../).

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// عرض النص ومعلومات الموقع لأول ظهور للنص
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


