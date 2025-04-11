---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Font-egenskap. Hämtar eller ställer in ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att vara delmängd och inbäddat
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset-egenskap

Hämtar eller ställer in ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserat på IFont kommer automatiskt att vara delmängd och inbäddat

```csharp
public bool IsSubset { get; set; }
```

## Exempel

Exemplet visar hur man söker text på första sidan och får värdet som indikerar om teckensnittet är en delmängd.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [Font](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)