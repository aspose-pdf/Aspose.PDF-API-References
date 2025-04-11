---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Eigenschaft. Erhält die Sammlung von Suchvorkommen, die mit TextFragment-Objekten präsentiert werden
type: docs
weight: 90
url: /de/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments-Eigenschaft

Erhält die Sammlung von Suchvorkommen, die mit [`TextFragment`](../../textfragment/) Objekten präsentiert werden.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments findet und alle Suchvorkommen durch neuen Text ersetzt.

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

### Siehe auch

* Klasse [TextFragmentCollection](../../textfragmentcollection/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)