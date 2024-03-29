---
title: Phrase
second_title: Aspose.PDF لمرجع .NET API
description: الحصول على أو تعيين العبارة التي يحتوي عليها ملفTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber عمليات البحث في مستند أو صفحة PDF.
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

الحصول على أو تعيين العبارة التي يحتوي عليها ملف[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث في مستند أو صفحة PDF.

```csharp
public string Phrase { get; set; }
```

### أمثلة

يوضح المثال كيفية إجراء نص البحث عدة مرات وإجراء عمليات استبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "مرحبًا"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// ابحث عن كلمة أخرى واستبدلها
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
