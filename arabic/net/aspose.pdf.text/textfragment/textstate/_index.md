---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragment. تحصل أو تعين حالة النص للنص الذي يمثله كائن TextFragment
type: docs
weight: 150
url: /ar/net/aspose.pdf.text/textfragment/textstate/
---
## خاصية TextFragment.TextState

تحصل أو تعين حالة النص للنص الذي يمثله كائن [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## ملاحظات

توفر وسيلة لتغيير الخصائص التالية للنص: الخط حجم الخط نمط الخط لون المقدمة لون الخلفية

## أمثلة

توضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)