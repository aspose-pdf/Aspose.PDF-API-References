---
title: "Font.IsSubset"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Font. تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تقليصه وتضمينه تلقائيًا"
type: docs
weight: 70
url: /ar/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيُقسم تلقائيًا ويُضمّن.

```csharp
public bool IsSubset { get; set; }
```

## أمثلة

يوضح المثال كيفية البحث عن النص في الصفحة الأولى والحصول على القيمة التي تشير إلى ما إذا كان الخط مجموعة فرعية.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// عرض قيمة IsSubset للخط في أول ظهور للنص
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


