---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-egenskap. Hämtar eller ställer in String textobjekt som TextFragment-objektet representerar
type: docs
weight: 130
url: /sv/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text-egenskap

Hämtar eller ställer in String textobjekt som [`TextFragment`](../) objektet representerar.

```csharp
public string Text { get; set; }
```

## Exempel

Exemplet visar hur man söker efter en text och ersätter första förekomsten som representeras av [`TextFragment`](../) objektet.

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

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [TextFragment](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)