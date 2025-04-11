---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragmentAbsorber. تحصل أو تعين العبارة التي يبحث عنها TextFragmentAbsorber في مستند PDF أو الصفحة
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## خاصية TextFragmentAbsorber.Phrase

تحصل أو تعين العبارة التي يبحث عنها [`TextFragmentAbsorber`](../) في مستند PDF أو الصفحة.

```csharp
public string Phrase { get; set; }
```

## أمثلة

توضح المثال كيفية إجراء بحث عن النص عدة مرات وإجراء استبدالات للنص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)