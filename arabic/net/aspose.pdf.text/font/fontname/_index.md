---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: خاصية الخط. تحصل على اسم الخط لكائن الخط
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/font/fontname/
---
## خاصية Font.FontName

تحصل على اسم الخط لكائن [`Font`](../).

```csharp
public string FontName { get; }
```

## أمثلة

توضح المثال كيفية البحث عن النص في الصفحة الأولى وعرض اسم الخط لأول ظهور للنص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)