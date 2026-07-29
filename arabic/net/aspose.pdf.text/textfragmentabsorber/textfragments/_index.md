---
title: "TextFragmentAbsorber.TextFragments"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragmentAbsorber. تحصل على مجموعة حدوث عمليات البحث التي يتم تمثيلها بكائنات TextFragment"
type: docs
weight: 90
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

تحصل على مجموعة حدوث عمليات البحث التي يتم تمثيلها بكائنات [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال جميع حدوث عمليات البحث بنص جديد.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// غيّر نص جميع حالات البحث
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


