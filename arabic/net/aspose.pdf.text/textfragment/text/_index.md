---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragment. تحصل أو تعين كائن نص من نوع String الذي تمثله كائن TextFragment
type: docs
weight: 130
url: /ar/net/aspose.pdf.text/textfragment/text/
---
## خاصية TextFragment.Text

تحصل أو تعين كائن نص من نوع String الذي يمثله كائن [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## أمثلة

توضح المثال كيفية البحث عن نص واستبدال أول ظهور ممثل بكائن [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)