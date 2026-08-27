---
title: "Font.IsEmbedded"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Font. تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيتم تقليصه وتضمينه تلقائيًا"
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيُقسم تلقائيًا ويُضمّن.

```csharp
public bool IsEmbedded { get; set; }
```

## أمثلة

يوضح المثال التالي كيفية العثور على خط، وضع علامة عليه كمدمَج، البحث عن النص في صفحة المستند واستبدال خط النص.

```csharp
// إنشاء خط وتحديده ليتم تضمينه
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// قبول الماصة للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير الخط لأول ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


