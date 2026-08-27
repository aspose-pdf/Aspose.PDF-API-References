---
title: "TextFragment.TextState"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragment. تحصل أو تعيّن حالة النص للنص الذي يمثله كائن TextFragment"
type: docs
weight: 150
url: /ar/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

يحصل أو يعين حالة النص للنص الذي يمثله كائن [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## ملاحظات

يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor

## أمثلة

يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن `TextState`.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير لون المقدمة للظهور الأول للنص
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// تغيير حجم الخط للظهور الأول للنص
absorber.TextFragments[1].TextState.FontSize = 15;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


