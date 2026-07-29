---
title: "TextFragmentAbsorber.Phrase"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragmentAbsorber. تحصّل أو تعيين العبارة التي يبحث عنها TextFragmentAbsorber في مستند PDF أو الصفحة."
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

تحصّل أو تعيين العبارة التي يبحث عنها `[`TextFragmentAbsorber`](../)` في مستند PDF أو الصفحة.

```csharp
public string Phrase { get; set; }
```

## أمثلة

يوضح المثال كيفية إجراء بحث عن النص عدة مرات وإجراء استبدالات النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع حالات النص "hello".
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// ابحث عن كلمة أخرى واستبدلها
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


