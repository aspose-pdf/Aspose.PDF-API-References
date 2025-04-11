---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-egenskap. Hämtar samling av sökförekomster som presenteras med TextFragment-objekt
type: docs
weight: 90
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments-egenskap

Hämtar samling av sökförekomster som presenteras med [`TextFragment`](../../textfragment/) objekt.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter alla sökförekomster med ny text.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [TextFragmentCollection](../../textfragmentcollection/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)