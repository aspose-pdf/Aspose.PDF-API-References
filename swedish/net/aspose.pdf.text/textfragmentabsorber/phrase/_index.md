---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-egenskap. Hämtar eller ställer in frasen som TextFragmentAbsorber söker på PDF-dokumentet eller sidan
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase-egenskap

Hämtar eller ställer in frasen som [`TextFragmentAbsorber`](../) söker på PDF-dokumentet eller sidan.

```csharp
public string Phrase { get; set; }
```

## Exempel

Exemplet visar hur man utför söktext flera gånger och gör textbyten.

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

### Se Även

* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)