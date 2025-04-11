---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Eigenschaft. Ruft Suchoptionen ab oder legt sie fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken
type: docs
weight: 110
url: /de/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions-Eigenschaft

Ruft Suchoptionen ab oder legt sie fest. Die Optionen ermöglichen die Suche mit regulären Ausdrücken.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man Text mit regulären Ausdrücken sucht.

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

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)