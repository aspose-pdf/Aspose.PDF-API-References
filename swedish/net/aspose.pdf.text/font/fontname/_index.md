---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Font-egenskap. Hämtar teckensnittets namn för Font-objektet
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/font/fontname/
---
## Font.FontName-egenskap

Hämtar teckensnittets namn för [`Font`](../) objektet.

```csharp
public string FontName { get; }
```

## Exempel

Exemplet visar hur man söker text på första sidan och visar teckensnittets namn för den första textförekomsten.

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

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [Font](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)