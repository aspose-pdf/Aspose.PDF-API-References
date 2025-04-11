---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-egenskap. Hämtar eller ställer in sökalternativ. Alternativen möjliggör sökning med hjälp av reguljära uttryck
type: docs
weight: 110
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions-egenskap

Hämtar eller ställer in sökalternativ. Alternativen möjliggör sökning med hjälp av reguljära uttryck.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Exempel

Exemplet visar hur man utför sökning av text med hjälp av regulärt uttryck.

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

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)