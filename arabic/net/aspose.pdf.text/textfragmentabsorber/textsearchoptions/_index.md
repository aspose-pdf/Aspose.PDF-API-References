---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextFragmentAbsorber. تحصل أو تعين خيارات البحث. تتيح الخيارات البحث باستخدام التعبيرات العادية
type: docs
weight: 110
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## خاصية TextFragmentAbsorber.TextSearchOptions

تحصل أو تعين خيارات البحث. تتيح الخيارات البحث باستخدام التعبيرات العادية.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## أمثلة

توضح المثال كيفية إجراء بحث عن النص باستخدام التعبير العادي.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)