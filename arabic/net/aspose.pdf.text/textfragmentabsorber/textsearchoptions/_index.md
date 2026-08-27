---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragmentAbsorber. تحصل أو تعين خيارات البحث. تمكّن الخيارات البحث باستخدام التعابير النمطية"
type: docs
weight: 110
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

يحصل أو يعيّن خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## أمثلة

يوضح المثال كيفية إجراء بحث نص باستخدام التعبير النمطي.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// اجعل الـ absorber يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام التعبير النمطي.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// يجب أن نجد كلمة \"hello\" ونستبدلها بـ \"Hi\"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


