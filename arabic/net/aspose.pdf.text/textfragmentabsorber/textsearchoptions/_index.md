---
title: TextSearchOptions
second_title: Aspose.PDF لمرجع .NET API
description: الحصول على خيارات البحث أو تعيينها. تتيح الخيارات البحث باستخدام التعبيرات العادية.
type: docs
weight: 100
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

الحصول على خيارات البحث أو تعيينها. تتيح الخيارات البحث باستخدام التعبيرات العادية.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

### أمثلة

يوضح المثال كيفية إجراء نص البحث باستخدام التعبير العادي.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// اجعل الممتص يبحث عن كل الكلمات التي تبدأ بـ "h" وتنتهي "o" باستخدام التعبير النمطي.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// يجب أن نجد كلمة "hello" واستبدالها بـ "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf"); 
```

### أنظر أيضا

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->