---
title: TextFragments
second_title: Aspose.PDF لمرجع .NET API
description: الحصول على مجموعة من تكرارات البحث التي يتم تقديمها معTextFragmentaspose.pdf.text/textfragment الكائنات .
type: docs
weight: 80
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

الحصول على مجموعة من تكرارات البحث التي يتم تقديمها مع[`TextFragment`](../../textfragment) الكائنات .

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال جميع حالات البحث التي تحدث بنص جديد.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير نص جميع تكرارات البحث
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextFragmentCollection](../../textfragmentcollection)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->